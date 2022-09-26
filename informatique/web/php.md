# PHP

## POO (Programmation Orientée Objet)

```php
class Personne
{
    //Attributs
    private $nom;
    private $prenom;
    private $dateNaissance;
    private $salaire;
    public $nbEnfant;
    
    //Constructeur
    function __construct($nom, $prenom, $dateNaissance, $nbEnfant = 0)
    {
        $this->nom = $nom;
        $this->prenom = $prenom;
        $this->dateNaissandce = $dateNaissance;
        $this->nbEnfant = $nbEnfant;
    }
    
    
    //Accesseurs / Mutateurs
    public function setSalaire($valeur)
    {
        $this->salaire = $valeur;
    }
    public function getSalaire($valeur)
    {
        return $this->salaire;
    }
    
    
    //Méthodes
    public function age()
    {
        $date = new DateTime($this->dateNaissance);
        $now = new DateTime();
        $interval = $now->diff($date);
        return $interval->y;
    }
    
    public function argentPoche()
    {
        return $this->salaire / $this->nbEnfant;
    }
    
}
```

# PHP

## POO (Programmation Orientée Objet)

La base :

```php
class SimpleClass
{
    // Déclaration d'une propriété
    public $var = 'une valeur par défaut';
    public $var2 = 'une valeur par défaut';

    // Constructeur
    function __construct($var, $var2)
    {
        $this->var = $var;
        $this->var2 = $var2;
    }

    // Déclaration des méthodes
    public function displayVar() {
        echo $this->var;
    }

    public function setVar($var){
        $this->var = $var;
    }

    public function setVar($var, $var2){
        $this->var = $var;
        $this->var2 = $var2;
    }
}
```

Exemple plus concret :

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

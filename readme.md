# Test
```php
<?php

class User
{
    private $name;
    private $email;

    public function setName($name)
    {
        $this->name = $name;
    }

    public function setEmail($email)
    {
        $this->email = $email;
    }

    public function getName()
    {
        return $this->name;
    }

    public function getEmail()
    {
        return $this->name;
    }
}

$user = new User();
```
# Menu
1. Item_1;
2. Item_2;
3. Item_3:
    * subitem_1;
    * subitem_2.

# answer.pseudo
Jobspire Challenge

JOBSPIRE_CHALLENGE CONTROLLER:

<?php 

  function GetName($name)
  {
      $rand=rand(6,15);
      return $name.$rand;
  }
  
?>

JOBSPIRE_CHALLENGE_VIEW VIEW:

<?php

echo GetName('Ahmad');


?>

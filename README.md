<?php 
require_once 'conexao.php'; 
/*$id = $_POST['questao'];
$query = "SELECT * FROM questao WHERE idQuestao = $id";
$stmt = $conn->prepare($query);
$stmt->execute();
if ($stmt->rowCount()>0){
    echo "consulta realizada";
}
for($i=0; $i<count($id); $i++) {
    
    $query = "SELECT * FROM questao WHERE idQuestao = $id[$i]";
    $stmt = $conn->prepare($query);
    $stmt->execute();
    if ($stmt->rowCount()>0){
        echo "consulta realizada";
    }
}*/
    echo"$id[0]";

?>

<?php
// Verifica se o parâmetro 'min' está presente na consulta GET
$min = isset($_GET['min']) ? intval($_GET['min']) : 100;

// Verifica se o parâmetro 'max' está presente na consulta GET
$max = isset($_GET['max']) ? intval($_GET['max']) : 1000;

// Gera um valor aleatório entre $min e $max
$randomValue = rand($min, $max);

// Exibe o valor aleatório gerado sem decimais ou formatação
echo $randomValue;
?>

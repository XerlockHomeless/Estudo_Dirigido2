<?php

print "Insira o valor de A: ";
$a = fgets(STDIN);

if ($a == 0) {

    print "A não pode ser validado como 0 \n";
    exit;

}

print "Insira o valor de B: ";
$b = fgets(STDIN);

print "Insira o valor de C: ";
$c = fgets(STDIN);

    $Delta = (pow($b,2))-(4*$a*$c);

if ($Delta < 0) {

    print "Delta negativo: não possui raizes reais";
    exit;

}

elseif ($Delta == 0) {

        $X = -$b/2*$a;

    print "O valor de A é: $a";
    print "O valor de B é: $b";
    print "O valor de C é: $c";
    print "O valor de Δ é: $Delta \n";
    print "O valor de x é: $X \n";

}

elseif ($Delta > 0) {

        $X1 = (-$b-sqrt($Delta))/2*$a;
        $X2 = (-$b+sqrt($Delta))/2*$a;

    print "O valor de A é: $a";
    print "O valor de B é: $b";
    print "O valor de C é: $c";
    print "O valor de Δ é: $Delta \n";
    print "O valor de x1 é: $X1 \n";
    print "O valor de x2 é: $X2 \n";    

}

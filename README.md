<meta charset="UTF-8">
<script>
function calculaImc(altura, peso) {

    var imc = peso / (altura * altura);
    return imc;

}

var imcFlavio = calculaImc(1.71, 73);
var imcAmigo = calculaImc(1.72, 68);

mostra(imcFlavio);
mostra(imcAmigo);

</script>

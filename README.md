# EntregaFinalVacasAlPoder

mkdir entregaFinal
vim script // En modo edició empezamos a crear el prgograma que se nos pide


// La vaca que saluda:
echo "Saludos usuario!" | cowsay 
// Un texto que nos pregunte qué revisar:
echo "Por favor, introduce manualmente el directorio que quieras revisar: "
// Que haga un ls de dicho directorio y lo muestre una vaca 
read directorio
ls "$directorio" | cowsay
// Comando para que espere 3 segundos
sleep 3 

echo -e "\e[32mFin\e[0m" 

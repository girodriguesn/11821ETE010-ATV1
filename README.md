# 11821ETE010-ATV1

Lab 02

Neste laboratório criamos os arquivos de partida e o processo de compilação para um sistema Cortex-M.
Por fim, iniciamos o firmware para piscar o LED da placa STM32. Para a realização da atividade seguimos o passo a passo:


Criação de uma pasta para o novo projeto > Criação de um arquivo main.c, compilado utilizando o GNU Arm Embedded Toolchain > Criação de um arquivo Makefile para automatizar o processo de compilação > Criação do arquivo startup.c para executar as tarefas de inicialização do sistema e adição de seu processo de compilação ao Makefile
No final deste processo o objetivo do laboratório foi concluído.

Lab 03 

Neste laboratório continuamos a implementação do programa para piscar LED, escrevendo o programa para piscá-lo.
Para isto, foi necessário realizar os passos a seguir para adicionar aos arquivos do Lab 02:

Realizar uma cópia dos arquivos do Lab 02 para a pasta Lab 03 > Definir os endereços dos registradores, ajustando os valores para habilitar a porta GPIOC > Definir o pino PC13 ligado ao LED como saída através dos registrados do GPIOC > Realizar a análise dos arquivos objeto realocáveis por meio do objdump no cmd > Criação do arquivo linker script para combinar o código objeto em um único executável > Modificar o Makefile para chamar o linker e indicar objeto de entrada e arquivo de saída
No final deste processo o objetivo do laboratório foi concluído.

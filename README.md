# 11911EAU001-ATV1

Para realizar a atividade de laboratório de Sistemas Embarcados 1 foram seguidos os roteiros disponibilizados pelo professor. A primeira etapa é seguir o roteiro da ATV1 a.

No roteiro da ATV1 a é possível obter as informações para configuração do ambiente de desenvolvimento. Primeiramente é instalado o Ubuntu para utilizar o WSL por meio do Windows PowerShell, e são feitas algumas instalações de ferramentas básicas que serão utilizadas ao longo do curso, como por exemplo o compilador que será utilizado, e as ferramentas de gravação e depuração do código. As ferramentas de código aberto ST-LINK também podem ser utilizadas para gravar e depurar programas desenvolvidos para dispositivos STM32, e serão utilidas no curso. Por fim é instalado o Visual Studio Code, em que será utilizado para fazer a edição do código programado.
Após seguir as instruções do roteiro da ATV1 a o computador já estará pronto para desenvolver os projetos do curso. O próximo passo é seguir os roteiros dos laboratórios 2 e 3, ambos com o intuito de fazer um led piscar.

O intuito do roteiro do laboratório 2 é mostrar o processo de criação de todos os arquivos de partida e o processo de compilação para um sistema Cortex-M, além de começar o desenvolvimento para piscar o led integrado a placa de desenvolvimento STM32F411 Blackpill. Para automatizar o processo de compilação é utilizado a ferramenta "make", e que o código pode ser observado neste repositório na pasta "Makefile". Posteriormente é criado o arquivo de inicialização "startup" visto que não possuimos nenhum Sistema Operacional para realizar estas atividades e devemos prover o código necessário. O código para o arquivo "startup" também pode ser observado neste repositório.

Por fim é feito o roteiro do laboratório 3. Nele iremos desenvolver a nossa função principal "main". Ao longo do roteiro a ferramenta "make" é otimizada, e o código para acender o led integrado a placa de desenvolvimento STM32F411 Blackpill, e que pode ser visualizado neste relatório.
Após seguir e entender todas as instruções, a atividade 1 do laboratório de Sistemas Embarcados 1 está pronta.

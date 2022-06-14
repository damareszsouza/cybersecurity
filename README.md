# cybersecurity
Cyberchef
O canivete do exército suíço cibernético
CyberChef é um aplicativo web simples e intuitivo para realizar todos os tipos de operações "cibernéticas" em um navegador da web. Essas operações incluem codificação simples como XOR e Base64, criptografia mais complexa como AES, DES e Blowfish, criação de binários e hexdumps, compactação e descompactação de dados, cálculo de hashes e somas de verificação, análise de IPv6 e X.509, alteração de codificações de caracteres e muito mais .

A ferramenta foi projetada para permitir que analistas técnicos e não técnicos manipulem dados de maneiras complexas sem ter que lidar com ferramentas ou algoritmos complexos. Ele foi concebido, projetado, construído e aprimorado incrementalmente por um analista em seu tempo de inovação de 10% ao longo de vários anos.

Demonstração ao vivo
CyberChef ainda está em desenvolvimento ativo. Como resultado, não deve ser considerado um produto acabado. Ainda há testes e correção de bugs a serem feitos, novos recursos a serem adicionados e documentação adicional a ser escrita. Por favor, contribua!

As operações criptográficas no CyberChef não devem ser confiáveis ​​para fornecer segurança em qualquer situação. Nenhuma garantia é oferecida quanto à sua exatidão.

Uma demonstração ao vivo pode ser encontrada aqui - divirta-se!

Como funciona
Existem quatro áreas principais no CyberChef:

A caixa de entrada no canto superior direito, onde você pode colar, digitar ou arrastar o texto ou arquivo no qual deseja operar.
A caixa de saída no canto inferior direito, onde o resultado do seu processamento será exibido.
A lista de operações na extrema esquerda, onde você pode encontrar todas as operações que o CyberChef é capaz de realizar em listas categorizadas ou pesquisando.
A área da receita no meio, onde você pode arrastar as operações que deseja usar e especificar argumentos e opções.
Você pode usar quantas operações quiser de maneiras simples ou complexas. Alguns exemplos são os seguintes:

Decodificar uma string codificada em Base64
Converter uma data e hora para um fuso horário diferente
Analisar um endereço IPv6 Teredo
Converta dados de um hexdump e, em seguida, descompacte
Descriptografar e desmontar shellcode
Exibir vários carimbos de data/hora como datas completas
Realizar diferentes operações em dados de diferentes tipos
Use partes da entrada como argumentos para operações
Execute a descriptografia AES, extraindo o IV do início do fluxo de cifra
Detecte automaticamente várias camadas de codificação aninhada
Características
Arraste e solte
As operações podem ser arrastadas para dentro e para fora da lista de receitas ou reorganizadas.
Arquivos de até 2 GB podem ser arrastados sobre a caixa de entrada para carregá-los diretamente no navegador.
Assar Automático
Sempre que você modificar a entrada ou a receita, o CyberChef automaticamente "assará" para você e produzirá a saída imediatamente.
Isso pode ser desligado e operado manualmente se estiver afetando o desempenho (se a entrada for muito grande, por exemplo).
Detecção de codificação automatizada
O CyberChef usa várias técnicas para tentar detectar automaticamente em quais codificações seus dados estão. Se encontrar uma operação adequada que possa dar sentido aos seus dados, ele exibirá o ícone 'mágico' no campo Saída, no qual você pode clicar para decodificar seus dados.
Pontos de interrupção
Você pode definir pontos de interrupção em qualquer operação em sua receita para pausar a execução antes de executá-la.
Você também pode percorrer a receita uma operação por vez para ver a aparência dos dados em cada estágio.
Salvar e carregar receitas
Se você tiver uma receita incrível que sabe que vai querer usar novamente, basta clicar em "Salvar receita" e adicioná-la ao seu armazenamento local. Ele estará esperando por você na próxima vez que você visitar o CyberChef.
Você também pode copiar o URL, que inclui sua receita e entrada, para compartilhá-lo facilmente com outras pessoas.
Procurar
Se você souber o nome da operação que deseja ou uma palavra associada a ela, comece a digitá-la no campo de pesquisa e todas as operações correspondentes serão mostradas imediatamente.
Destacando
Ao destacar texto na entrada ou saída, os valores de deslocamento e comprimento serão exibidos e, se possível, os dados correspondentes serão destacados na saída ou entrada respectivamente (exemplo: destaque a palavra 'pergunta' na entrada para ver onde ele aparece na saída ).
Salvar no arquivo e carregar do arquivo
Você pode salvar a saída em um arquivo a qualquer momento ou carregar um arquivo arrastando e soltando-o no campo de entrada. Arquivos de até cerca de 2 GB são suportados (dependendo do seu navegador), no entanto, algumas operações podem levar muito tempo para serem executadas com tantos dados.
CyberChef é inteiramente do lado do cliente
Deve-se notar que nenhuma configuração ou entrada de sua receita (texto ou arquivos) é enviada para o servidor web CyberChef - todo o processamento é realizado no seu navegador, em seu próprio computador.
Devido a esse recurso, o CyberChef pode ser baixado e executado localmente. Você pode usar o link no canto superior esquerdo do aplicativo para baixar uma cópia completa do CyberChef e soltá-lo em uma máquina virtual, compartilhá-lo com outras pessoas ou hospedá-lo em uma rede fechada.
Links diretos
Ao manipular o hash de URL do CyberChef, você pode alterar as configurações iniciais com as quais a página é aberta. O formato éhttps://gchq.github.io/CyberChef/#recipe=Operation()&input=...

Os argumentos com suporte são recipe, input(codificado em Base64) e theme.

Suporte ao navegador
CyberChef é construído para suportar

Google Chrome 50+
Mozila Firefox 38+
Suporte para Node.js
O CyberChef foi desenvolvido para oferecer suporte total ao Node.js v10e suporte parcial ao v12. As importações nomeadas usando um especificador de importação profunda não funcionam no v12. Para obter mais informações, consulte a página da API do Node nas páginas do wiki do projeto

Contribuindo
Contributing a new operation to CyberChef is super easy! There is a quickstart script which will walk you through the process. If you can write basic JavaScript, you can write a CyberChef operation.

An installation walkthrough, how-to guides for adding new operations and themes, descriptions of the repository structure, available data types and coding conventions can all be found in the project wiki pages.

Push your changes to your fork.
Submit a pull request. If you are doing this for the first time, you will be prompted to sign the GCHQ Contributor Licence Agreement via the CLA assistant on the pull request. This will also ask whether you are happy for GCHQ to contact you about a token of thanks for your contribution, or about job opportunities at GCHQ.
Licencing
O CyberChef é lançado sob a licença Apache 2.0 e é coberto pelo Crown Copyright .


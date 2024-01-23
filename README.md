Description of the Exercise files. PT/EN

Test 1 - Acessa o site, realiza o download de um arquivo excel, le o arquivo, armazena os dados em uma fila no orchestrador, le essa fila(dados específicos) e os insere em campos de um site e clica em submit.

Test 1 - Access the website, download the files, read the files, and add them to the queue. Then input the data in a specific part of the website and click submit

Test 2 - Acessa o site, realiza o download de um arquivo excel, lê esse arquivo e utiliza o mesmo como forma de fila e percorre todas as informações, e insere oa dados especificados nos campos de um site e clica em submit.

Test 2 - Access the website, download the Excel file, read the file, and use it as a local queue. Then input the data in a specific section of the website and click submit.


P01 Exercise - Exercício realizado no ReFramework. Obtém as credenciais de um asset no Orchestrator, realiza o login em um site com elas, clica na opção 'work items' e, em seguida, percorre todas as páginas extraindo os dados específicos (WIID, TYPE, STATUS) no formato de tabela. Filtra os dados por TYPE = "WI5" e Status = "Open" e utiliza a tabela extraída como fila local. Percorre a fila e, para cada linha, utiliza o valor "WIID" extraído para gerar um link concatenando a URL + WIID. Com esse link gerado, acessa os 'Work Item Details' e extrai o ClientID, ClientName e ClientCountry. Em seguida, acessa um site no qual gera um código hash inserindo as informações extraídas anteriormente do cliente. Manipula a URL para cada cliente e acessa o 'Update Work Items', insere o código hash gerado anteriormente e altera o status para 'Completed'.


P01 Exercise - Exercise done in ReFramework. Retrieves credentials from an asset in Orchestrator, logs in to a website with them, clicks on the 'work items' option, and then navigates through all the pages, extracting specific data (WIID, TYPE, STATUS) in table format. Filters the data by TYPE = "WI5" and Status = "Open" and uses the extracted table as a local queue. Goes through the queue, and for each row, uses the extracted "WIID" value to generate a link by concatenating the URL + WIID. With this generated link, accesses the 'Work Item Details' and extracts the ClientID, ClientName, and ClientCountry. Then, accesses a site where it generates a hash code by inserting the previously extracted client information. Manipulates the URL for each client and accesses the 'Update Work Items', inserts the previously generated hash code, and changes the status to 'Completed'.


P02 Exercise - Exercício realizado no ReFramework. Obtém as credenciais de um asset no Orchestrator, realiza o login em um site com elas, clica na opção 'work items' e, em seguida, percorre todas as páginas extraindo os dados específicos (WIID, TYPE) no formato de tabela. Filtra os dados por TYPE = "WI4" e utiliza a tabela extraída como fila no Orchestrator. Percorre a fila e, para cada linha, utiliza o valor "WIID" extraído para gerar um link concatenando a URL + WIID. Com esse link gerado, acessa os 'Work Item Details' e extrai o 'TaxID'. Em seguida, acessa um site no qual insere o 'TaxID', faz o download dos relatórios mensais desse vendedor. Posteriormente, agrupa os arquivos mensais baixados em uma pasta única e realiza o upload anual dos arquivos consolidados para o site.7


P02 Exercise - Exercise done in ReFramework. Retrieves credentials from an asset in Orchestrator, logs in to a website with them, clicks on the 'work items' option, and then navigates through all the pages, extracting specific data (WIID, TYPE) in table format. Filters the data by TYPE = "WI4" and uses the extracted table as a queue in Orchestrator. Goes through the queue, and for each line, uses the extracted "WIID" value to generate a link by concatenating the URL + WIID. With this generated link, accesses the 'Work Item Details' and extracts the 'TaxID'. Then, accesses a site where it inserts the 'TaxID', downloads monthly reports for that vendor. Subsequently, consolidates the downloaded monthly files into a single folder and uploads the consolidated annual files to the site for each vendor.

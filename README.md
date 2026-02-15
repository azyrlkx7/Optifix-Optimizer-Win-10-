[Compativel APENAS com WiNDOWS 10]
esse Script (Optifix) faz as seguintes Modificações:


1. Gerenciamento de Serviços (Parada e Desativação)
O script interrompe e desativa permanentemente dezenas de serviços para liberar memória RAM e processamento, incluindo:


Rastreamento e Telemetria: DiagTrack, dmwappushservice, diagnosticshub.standardcollector.service. 


Recursos do Windows: WSearch (Busca), SysMain (antigo Superfetch), TrkWks (Links Distribuídos), WMPNetworkSvc (Windows Media Player). 


Rede e Acesso Remoto: RemoteRegistry, RemoteAccess, iphlpsvc (IP Helper), lmhosts. 


Outros Serviços: VSS (Shadow Copy), DoSvc (Otimização de Entrega), PrintWorkflow, SmsRouter, RetailDemo, TabletInputService, Bluetooth Support. 

2. Desativação de Tarefas Agendadas
Desativa rotinas automáticas do sistema para evitar picos de uso de CPU:


Experiência do Usuário: Microsoft Compatibility Appraiser, ProgramDataUpdater, Consolidator, UsbCeip. 
+4


Manutenção: WinSAT (Avaliação de sistema), DiskDiagnosticDataCollector, File History. 
+1


Office e Edge: Desativa atualizações automáticas do Microsoft Office e Microsoft Edge. 
+1


Navegadores de Terceiros: Desativa tarefas de atualização do Google Chrome e Brave. 

3. Privacidade e Telemetria (Registro do Windows)
Aplica restrições rigorosas para evitar o envio de dados para a Microsoft:


Bloqueio de Telemetria: Desativa o envio de dados de diagnóstico em vários níveis do registro. 
+4


SmartScreen e Cortana: Desativa o filtro SmartScreen e a assistente Cortana. 
+2


Sensores e Localização: Bloqueia o uso de sensores, serviços de localização e acesso à webcam/microfone. 
+3


Publicidade: Desativa o ID de anúncio e sugestões de conteúdo no menu iniciar. 
+4

4. Otimização de Rede e Internet

Alteração de DNS: Configura o DNS da Cloudflare (1.1.1.1 e 1.0.0.1) para IPv4 e IPv6 em todos os adaptadores. 
+2


Melhoria de Latência (Gaming): Ajusta TcpAckFrequency e TCPNoDelay para reduzir o ping. 
+2


Bloqueio via Hosts: Adiciona uma lista de domínios da Microsoft ao arquivo hosts para bloquear conexões de telemetria. 


Limpeza de Cache: Limpa o cache de DNS e reseta a pilha TCP/IP e Winsock. 
+2

5. Ajustes de Desempenho e Sistema

Memória: Desativa a paginação do núcleo do sistema (DisablePagingExecutive) e configura o tamanho do arquivo de paginação (pagefile.sys) para 2255MB. 
+1


Energia: Desativa a Hibernação (powercfg -h off) e o Inicialização Rápida. 


Plano de Energia: Força o uso de 100% da capacidade do processador e desativa economias de energia de barramento (ASPM). 
+2


Gráficos: Desativa transparências, efeitos visuais, sombras e acelera o tempo de resposta do menu. 
+2


Segurança (Performance): Desativa a Segurança Baseada em Virtualização (VBS) e Proteção de Integridade de Código por Hypervisor para ganhar FPS. 
+2

6. Configurações de Navegadores (Brave, Chrome, Firefox, Opera)

Firefox: Cria um arquivo de políticas (policies.json) para desativar telemetria, estudos e o recurso "Pocket". 


Brave/Chrome: Desativa envio de métricas, sincronização forçada e recursos de "limpeza" do Chrome. 


Opera: Desativa relatórios de métricas, serviços de IA (Aria) e VPN nativa via registro. 

7. Limpeza de Arquivos Temporários
Apaga todos os arquivos das pastas:


%TEMP% (Temporários do usuário). 


C:\Windows\Temp (Temporários do sistema). 


Prefetch (Dados de pré-carregamento). 


SoftwareDistribution\Download (Arquivos do Windows Update). 

Limpa o cache de fontes do Windows.

_______________________________________________________________________________________________________________________________

ele e totalmente focado em otimização e desempenho, faz modificações profundas no sistema, inclusive no kernel, Use por conta e risco.
(foi testado, mais não pode ser 100% seguro)

focado em otimização no sistema operacional: Windows 10
versão do windows testada: 22H2
versões do windows 10 compativeis: Todas

ele pode até funcionar em outros windows (windows 7/8.1) mais pode causar instabilidade e falhas graves.

ele e compativel com todas as edições do windows (home, Pro e etc..).

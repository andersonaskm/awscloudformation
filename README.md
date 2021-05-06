# AWS Cloud Formation
AWS Cloud Formation stack templates

Template para criação de uma instância EC2 na AWS.

Possui os seguintes componentes:

- LogRole - role de logs
- LogRoleInstanceProfile - perfil de instância para logs
- CloudFormationLogs: grupo de logs
- WebServer: instância EC2 para aplicações Web
- WebServerSecurityGroup: security group para a instância EC2
- IpAddress: IP dinâmica
- IpAssoc: associação de IP com a instância EC2
- 404MetricFilter: filtro para falhas 404s
- BytesTransferredMetricFilter: filtro pra quantidade de dados transferidos
- 404Alarm: alarme para quantidade de erros 404s
- BandwidthAlarm: alarme para consumo de quantidade de dados
- CPUAlarm: alarme para utilização de CPU
- MemoryAlarm: alarme sobre utilização de memória pela aplicação
- AlarmNotificationTopic: tópico no qual serão enviado os emails de alertas

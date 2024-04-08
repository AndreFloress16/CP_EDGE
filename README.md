Check Point 1 - Edge Computing
André Luiz dos Santos Flores - RM:554952
Gabriel Máximo Kaupa - RM:555879
Guilherme Lunghini Teixeira - RM:556892

Desenvolvemos um sistema usando o Arduino, que é capaz de capturar informações sobre a luminosidade. Para fazer isso, utilizamos um sensor de luminosidade conectado ao Arduino, esse sensor detecta a luz do led e manda essa informação como um sinal elétrico para o Arduino. Com isso programamos para realizar as ações com base na luz do led detectada.

Com os dados coletados pelo sistema de luminosidade que desenvolvemos, colocamos um sistema de alarme ligado aos Leds para sinalizar de acordo com o que foi pedido, com um sistema de três cores: Verde para indicar que está tudo bem, amarelo para indicar níveis de alerta e vermelho para indicar problemas. Quando estiver dentro dos limites estipulados como normais, o Arduino acenderá o led verde, se ultrapassar um limite de alerta acenderá o led amarelo e quando estiver fora dos limites aceitáveis acenderá o led vermelho, esse sistema oferece uma maneira fácil e rápida de identificar as condições do ambiente, permitindo uma resposta imediata caso aconteça variações significativas na luminosidade.


Além do sistema de leds, adicionamos um buzzer ao sistema quando estiver em nível de alerta, Quando o Arduino detectar que a luz dos Leds estão em níveis de alerta, ele vai ativar o buzzer para soar por um período de 3 segundos, fazendo que seja um alerta sonoro claro e perceptível ao usuário. E se continuar em níveis de alerta, o Arduino continuará a acionar o buzzer repetidamente.
Isso faz com que essa adição feita, complemente os Leds, fornecendo uma camada adicional de alerta para garatir que p usuário seja notificado imediatamente quando ocorrer uma condição critica, tornando o sistema mais eficaz em manter o usuário informado sobre as condições do sistema.

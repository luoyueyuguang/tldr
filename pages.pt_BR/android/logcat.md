# logcat

> Despeja um registro de mensagens do sistema.
> Mais informações: <https://developer.android.com/tools/logcat>.

- Exibe a saída do registro:

`logcat`

- Salva a saída da mensagem de registro em um arquivo:

`logcat -f {{caminho/para/arquivo}}`

- Exibe apenas linhas em que a mensagem de registro corresponda a uma expressão regular:

`logcat --regex {{expressao_regular}}`

- Exibe logs para um PID específico:

`logcat --pid {{pid}}`

- Exibe logs de processo de um pacote específico:

`logcat --pid $(pidof -s {{pacote}})`

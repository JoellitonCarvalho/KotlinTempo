# KotlinTempo

Aplicativo meteorológico Android simples desenvolvido em kotlin, demonstrando o uso de RxJava, Retrofit e implementando MVP.

# Visão geral
Aplicativo de clima criado usando o [Weather Api](https://market.mashape.com/fyhao/weather-13) do mercado Mashape.
Este não deve ser um aplicativo em escala de produção, destina-se a demonstrar a implementação da arquitetura **MVP** em Kotlin usando as seguintes bibliotecas:
* RxJava
* Retrofit

##### Ainda se você observar algum problema ou sugestão, sinta-se à vontade para abrir um [problema](https:/https://github.com/JoellitonCarvalho/KotlinTempo/issues/new)

### Fluxo geral de dados
* Verifique se há dados em cache presentes no arquivo interno, se sim, carregue os dados em cache.
* Recupere a latitude e longitude do usuário.
* Solicitar dados da Weather Api
* Se os dados forem recebidos, armazene-os em um arquivo interno e mostre os dados atualizados ao usuário.
* Se houver erro, notifique o usuário sobre isso.

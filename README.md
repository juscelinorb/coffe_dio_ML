# Exemplo de pesquisa usando Serviços de IA do Azure da Microsoft
---

## O exemplo imagina uma cafeteria que está em várias cidades


### Então vamos seguir o seguinte percurso:

<table>
  <thead>
    <tr align="left">
      <th>Nº</th>
      <th>Etapas</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Criar recursos do Azure</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Extrair dados de uma fonte de dados</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Enriqueça os dados com habilidades de IA</td>  
    </tr>
    <tr>
      <td>04</td>
      <td>Usar o indexador do Azure no portal do Azure</td>    
    </tr>
    <tr>
      <td>05</td>
      <td>Consultar o seu índice de pesquisa</td>    
    </tr>
    <tr>
      <td>06</td>
      <td>Revisar os resultados salvos em uma Loja de Conhecimento</td>    
    </tr>
  </tbody>
</table>


Recursos do Azure necessários
---

A solução que você criará para o Fourth Coffee requer os seguintes recursos da sua assinatura do Azure:

*   Um recurso **de Pesquisa de IA do Azure**, que gerenciará indexação e consulta.
*   Um recurso **de serviços de IA do Azure**, que fornece serviços de IA para habilidades que sua solução de pesquisa pode usar para enriquecer os dados na fonte de dados com insights gerados por IA.
    
    > **Nota** Os recursos dos seus serviços de Pesquisa de IA do Azure e do Azure AI devem estar no mesmo local!
    
*   Uma **conta de armazenamento** com contêineres de blob, que armazenará documentos brutos e outras coleções de tabelas, objetos ou arquivos.


> [!NOTE]   
> Você poderá seguir por aqui.
> Link do exemplo: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
---

![Percorrendo processos](https://img.shields.io/badge/Percorrendo%20os%20processos:-E94D5F?style=for-the-badge)


### Depois de criados os recursos conforme link de exemplo acima teremos:

![Recursos do microsoft learning](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/recursos_criados.jpg)

>[!NOTE]
> Conferimos então os recursos criados: 
> O Serviço de AI Azure,
> o Serviço de Pesquisa e
> a Conta de Armazenamento.


### Criaremos o contêiner onde gardaremos os dados

![Criação do Contêiner](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/conteiner.jpg)

### Dados adicionados

![Criação do Contêiner](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/dados_conteiner.jpg)

### Vá para o Serviço de Pesquisa

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_1.jpg)

### Importe os dados

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_2.jpg)

### Na tela de importação faça conforme o exemplo do link escolhendo Armazenamento de Blob do Azure

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_3.jpg)

### Prossiga escolhendo uma conexão já existente 

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_5.jpg)

### Depois de configurado e criado vai aparecer o resultado

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_7.jpg)

### Chegando a caixa de pesquisa

![Serviço de Pesquisa](https://github.com/juscelinorb/coffe_dio_ML/blob/main/imagens/Screenshot_8.jpg)
---

Caso queira verificar os exemplos de pesquisas continue até o fim dos exemplos.


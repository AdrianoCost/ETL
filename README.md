   <h1>Projeto ETL CoderHouse</h1>
    <h2>Autor: Adriano Costa</h2>
    <h2>Sobre o Projeto</h2>
    <p>Este projeto é uma implementação de um processo de Extração, Transformação e Carregamento (ETL) desenvolvido em Python para o curso da CoderHouse. O código realiza uma requisição à API RestCountries para extrair dados. Posteriormente, esses dados são carregados em três DataFrames específicos utilizando a biblioteca pandas. Cada DataFrame armazena um conjunto diferente de informações extraídas da API. Finalmente, os três DataFrames são mesclados em um único DataFrame através de uma operação de mesclagem, proporcionando uma visão unificada dos dados. Este processo de ETL permite a manipulação e análise eficiente dos dados encontrados da API RestCountries.</p>
    <h2>Bibliotecas e linguagens Utilizadas no projeto</h2>
    <ul>
        <li><b>Python</b>: Linguagem de programação usada para desenvolver o projeto.</li>
        <li><b>Pandas</b>: Biblioteca usada para manipulação e análise de dados.</li>
        <li><b>Requests</b>: Biblioteca usada para fazer requisições HTTP.</li>
        <li><b>plye</b>:Biblioteca usada para disparar as notificações.</li>
    </ul>
    <h2>Como Executar o Projeto</h2>
    <h3>Pré-requisitos</h3>
    <ul>
        <li>Python 3.x</li>
        <li>Virtualenv</li>
    </ul>
    <h3>Passos para Execução</h3>
    <ol>
        <li>Navegue até o diretório do projeto: Use o comando `cd` para navegar até o diretório do projeto.</li>
       <br>
        <li>Ative o ambiente virtual: O projeto vem com um ambiente virtual que já tem todas as dependências necessárias instaladas. Você pode ativá-lo usando o seguinte comando:</li>
       <br>
        <pre><code>
        source venv/bin/activate  # No Linux ou MacOS
        venv\Scripts\activate     # No Windows
        </code></pre>
       <br>
        <li>Execute o script Python: Finalmente, você pode executar o script Python que contém o código ETL.</li>
    </ol>

<div>

<h1>Swim -Adaptado-</h1> 


<p>
Os arquivos do repositório demonstram o SWIM de forma simples, para serem utilizados como teste de sistemas adaptativos.

Acesse <a href="https://github.com/cps-sei/swim">Esse link</a> para informações completas sobre o SWIM e suas diversas formas de utilização.

</p>

<h3>
também precisará de previamente instalado
</h3>

<ul>
    <li>
        Docker
    </li>
    <li>
        Docker CLI
    </li>
    <li>
        docker-compose compatível com a versão 3!
    </li>
</ul>

<h3>
    Passos para rodar o servidor de simulações SWIM.
</h3>

<ul>
    <li>
       Faça o download desse repositório.
    </li>
    <li>
        <p>
            Após o download, abra o terminal na pasta do projeto, e digite o comando       
        </p>
        <em>
            docker-compose up
        </em>
        <p>
            <a href="https://github.com/cps-sei/swim">Esse link</a> dá mais informações sobre o ambiente de simulação SWIM.
        </p>
    </li>
    <li>
        Após rodar o container, acesse em seu navegador de preferência o endereco <em>localhost:6901</em>,
        aparecerá um formulário pedindo uma senha para acessar o sistema no modo gráfico. A senha para acesso é <em>vncpassword</em>.
        Se acha necessário, acesse o arquivo de configuração <em>docker-compose.yml</em> e configure o mapeamento de portas como bem desejar.
    </li>
    <li>
        Já dentro do sistema que foi aberto no navegador, siga até o diretório <em>/headless/seams-swim/swim/simulations/swim/</em>.
    </li>
    <li>
        Dentro da pasta, abra o terminal, e digite o comando <em>./run.sh Reactive 0..2</em>.
    </li>
    <li>
        Após isso, o swim estará rodando em sua maquina, mapeada na porta 4242. ou em alguma outra porta caso tenha feita alguma alteração n arquivo de configuração.
    </li>
</ul>


</div>
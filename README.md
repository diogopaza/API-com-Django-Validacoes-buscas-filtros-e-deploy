# API-com-Django-Validacoes-buscas-filtros-e-deploy

<h3>Deploy com Django</h3>
<ul>
  <li><strong>pip freeze requirements.txt</strong> === atualiza as dependencias necessarias no arquivo requirements.txt;</li>
  <li><strong>ALLOWED_HOSTS = ['*']</strong> === no arquivo settings.py é necessario definir esta configuracao;</li>
  <li><strong>sudo apt install python3.10-venv</strong> === instalando o ambiente virtual do Python;</li>  
  <li><strong>sudo python3 -m venv venv</strong> === criacao o ambiente virtual do Python;</li>
  <li><strong>source venv/bin/activate</strong> === ativando o ambiente virtual do Python;</li>
  <li><strong>pip install -r requirement.txt</strong> === trazendo todas as bilbiotecas para rodar o projeto;</li>
  <li><strong>é preciso liberar a porta no EC2 da AWS por exemplo</strong></li>
</ul>

<h4>Aplicacao rodando em segundo plano no Linux Ubuntu - <strong>API-com-Django-Validacoes-buscas-filtros-e-deploy - repositorio original )</strong></h4>
<ul>
  <li><strong>screen -list</strong> === lista as sessoes executadas em segundo plano;</li>
  <li><strong>screen -S nomeDoApp</strong> === prepara o ambiente para ficar sendo executado em segundo plano, após esse comando dentro da pasta onde esta o app, coloca-se o serviço para rodar, neste exemplo python3 manage 0.0.0.0:8000 - <strong>notar no final do comando 0.0.0.0:8000 definindo que a porta 8000 estara liberada para todas as interfaces de rede e nao apenas a 127.0.0.1 como o padrao usado na maquina local</strong>;</li>
</ul>
</ul>

// Pipeline do Jenkins da VM (icaromelodev.com.br/jenkins). Builda toda branch; a main publica em produção.
@Library('vm') _

siteEstatico(build: 'bash scripts/build.sh', saida: 'site', pasta: 'brain', nginx: 'brain')

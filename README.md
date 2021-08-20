# PASTORABUS
# INTRODUÇÃO

A cidade de Quixadá no Estado do Ceará, é conhecida como um polo estudantil com a presença de diversas universidades, dentre elas o Instituto Federal do Ceará (IFCE) e a Universidade Federal do Ceará (UFC - Campus Quixadá). Ambas localizadas a aproximadamente 4,9 km do centro da cidade (Praça José de Barros), o que torna necessário o uso de transporte universitário. Em 2007, a prefeitura de Quixadá fez um acordo, juntamente com os campus federais, assumindo a responsabilidade de transportar a custo zero os estudantes universitários até que fosse implementado linhas urbanas (G1, 2019).
Em 2013, a então presidenta Dilma Rousseff (PT), promulgou uma ementa da lei 12.816/13, que autoriza os gestores municipais a utilizarem o Fundo Nacional de Desenvolvimento (FNDE), para regulamentar o transporte escolar para uso universitário. Mesmo após o acordo feito pela Prefeitura Municipal de Quixadá e o direito ao transporte escolar universitário previsto em constituição, a realidade vivida é outra, e isso representa prejuízos em vários aspectos para os alunos dos campus.
No ano de 2019, ainda não foi implementado linhas urbanas de ônibus em Quixadá e existem três ônibus que fazem o percurso da Praça José de Barros para os campus UFC/IFCE, sendo um disponibilizado pela UFC e os outros dois pela Prefeitura Municipal de Quixadá - CE. A pequena quantidade juntamente com a má qualidade dos ônibus disponibilizados geram incertezas para os usuários, que não sabem o horário correto e nem se haverá ônibus fazendo o trajeto. Para Françoso e Mello (2016), as redes de transportes são fundamentais na sociedade atual, por representarem uma influência direta na qualidade de vida e na eficiência dos transportes coletivos. 
A proposta inicial deste projeto é o desenvolvimento de um aplicativo que será possível visualizar os horários previstos para determinado ônibus passar em uma parada do trajeto. A localização dos ônibus passará em tempo real para os usuários do sistema por meio do compartilhamento da localização. Com isso será possível saber onde o ônibus está e qual o tempo de espera para que esse mesmo ônibus faça o mesmo percurso outra vez.


# FUNCIONALIDADES 

Nesse tópico será mostrado as funcionalidades do sistema.


# CRUD do sistema

O cadastro de ônibus e paradas será usando para que o sistema tenha as informações
necessárias, tanto dos ônibus quanto das paradas, para que o usuário possa consultar essas
informações.
Na etapa de cadastro de paradas vai ser registrado todos os pontos de espera que
compõem o percurso do ônibus universitário. As informações que vão ser salvas sobre
essas posições são: fotos do local, informação sobre a sua posição (cruzamento ou local
exato da parada), latitude e longitude referente ao local.
Na etapa de cadastro do ônibus, vai ser catalogado o transporte universitário da
UFC que faz o percurso Praça José de Barros/IFCE e IFCE/Praça José de Barros. As
informações que serão armazenadas será o itinerário, imagem e descrição do ônibus.

# Confirmação de compartilhamento e verificar localização compartilhada
	
O Google Developers (2021) define uma sequência de passos necessários para que
seja possível solicitar o acesso à localização do usuário. Essa solicitação é necessária
como uma forma de proteger a privacidade do usuário que usam os aplicativos com
serviços de localização.
No sistema será possível que o usuário que esteja dentro do ônibus compartilhe
sua localização para identificar a posição do ônibus, como uma forma de não permitir 
compartilhamento que não está dentro da rota do ônibus será necessário desenvolver um
verificador dessa localização compartilhada.

# Identificar posição do ônibus

Para identificar a posição do ônibus, vai ser seguido uma sequência de passos
lógicos usando os dados que foram armazenados pelo verificador de localização
compartilhada no Banco de dados da aplicação.

# Informações sobre o APP

Para informar o usuário sobre como o app funciona, será criado uma tela onde
todas essas informações estarão contidas de forma clara para o entendimento do usuário
para que ele possa usar o app sem nem uma dificuldade.



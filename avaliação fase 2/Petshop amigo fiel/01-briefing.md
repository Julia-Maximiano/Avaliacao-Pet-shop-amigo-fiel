# Briefing do Projeto — [PetShop Amigo Fiel]

## 1 - Contexto
[Quem é o cliente? O que o petshop faz? Quem trabalha nele?]
O nosso cliente se chama Ricardo
É um estabelecimento de banho e tosa para animais de estimação
bianca também trabalha em uma sala no petshop como tosadora autônoma

## 2 - Problema
[Como os agendamentos são feitos hoje? E o que dá errado?] 
Os agendamentos são feitos por telefone e anotados em uma única agenda de papel compartilhada. O erro é que isto pode causar marcações no mesmo horário, pois Ricardo e Bianca nem sempre conseguem visualizar as anotações um do outro.

## 3 - Objetivos
[O que o sistema deve alcançar] 
Organizar os agendamentos, cadastrar tutores e pets, registrar informações de saúde dos animais e permitir o controle dos horários utilizados pelos dois.

## 4 - Usúarios
[Quem vai usar o sistema, e como? (mais de um perfil?)]
Ricardo, proprietário do pet shop, e Bianca, tosadora autônoma. Ambos utilizarão o sistema para organizar os atendimentos e consultar os agendamentos.
Então serão dois perfis

## 5 - Escopo incluído
[As necessidades reais identificadas na entrevista] 
Cadastro de tutores; cadastro de pets; registro de raça, porte, alergias e observações de saúde; agendamento de banhos e tosas; consulta dos horários e identificação do responsavel pelo serviço

## 6 - Escopo excluído
[Os desejos mencionados que não fazem parte desta versão, com justificativa] 
Envio automático de fotos dos pets pelo WhatsApp
Justificativa: Sistema de permissões diferentes para Ricardo e Bianca, pois o prazo de dois meses e a limitação de orçamento não permitem desenvolver essa funcionalidade nesta versão.

## 7 - Restrições
[Prazo, e as informações técnicas complementares (seção 5)] 
O sistema deve ficar pronto em dois meses
ser desenvolvido em Python 3.11 ou superior, utilizar banco de dados MySQL em servidor, manter as credenciais do banco fora do código-fonte, comunicar-se por HTTP com dados JSON e proteger as senhas com algoritmo de hash reconhecido.

## 8 - Critérios de sucesso
[Como saber se o sistema resolveu o problema relatado]
Testes para sabermos se os tutores e pets poderão ser cadastrados; os dados de saúde dos animais estarão registrados; os agendamentos poderão ser consultados; os conflitos de horários do mesmo pet serão evitados; e os profissionais conseguirão organizar melhor os atendimentos.

Json Requests - urls

*CONFIGURATIONS*
GET - http://localhost:8080/swagger-ui.html
GET - http://localhost:8080/actuator


GET - http://localhost:8080/topicos
GET - http://localhost:8080/topicos/2

POST - http://localhost:8080/auth 
{
	"email": "aluno@email.com",
	"senha": "123456"
}

POST - http://localhost:8080/topicos
{
	"titulo": "NoVo tópico",
	"mensagem": "Mensagem teste",
	"nomeCurso": "Spring Boot"
}

PUT - http://localhost:8080/topicos/1
{
	"titulo": "NoVo tópico 2",
	"mensagem": "Mensagem teste"
}

DEL - http://localhost:8080/topicos/3 

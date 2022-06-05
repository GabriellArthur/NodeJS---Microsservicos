# Princípios de microsserviços

- Única responsabilidade dentro do domínio
   - O que é dominio (Domain-Driven Design)
   
- Autonomia (sem dependências entre serviços)

# Ganhos 

- Independência
   - Times
   - Github
   - CI/CD

- Fácil manutenção
   - Menos código
   - Menos responsabilidade
   - Menos testes
   - Ambiente de dev mais enxuto

- Escalonamento independente

# Desafios

- Observabilidade
- Comunicação
- Resiliência a falhas

# Conceitos Importantes

- Isolar por domínio
   - A mesma entidade pode ser representada de formas diferentes em cada domínio
- Banco de dados isolados
- Comunicação assíncrona

# Hands-on

# App

Um aplicação que simula o recebimento de uma compra e envia os dados do produtos comprados para outra plataforma "liberar o acesso" do usuário ao produto.

# Ferramentas

- Kafka
- Node.js
- TypeScript  
- PostgreSQL
# Desafio-1---Landing-Page
Links :
Planilha: https://docs.google.com/spreadsheets/d/1xh3VsmTt9dqFuHt7euYc-N4hXqQn8LtPYJoqTOym4SY/edit?usp=sharing
Site: https://mablerarquitetura.netlify.app/


Esta é uma Landing Page criada para completar o  Desafio 1 do módulo base do curso de Tecnologia da Escola DNC

O projeto consistia na criaçãode uma Landing Page em um cenário ficticio dentro do seguinte contexto:

"Um gerente de recrutamento de uma empresa de tecnologia e está procurando um
novo desenvolvedor para se juntar à equipe, e te contatou para a proposta de trabalho.
Desafio: Desenvolva uma Landing Page 2
Para avaliar as habilidades dos candidatos, ele decidiu propor um desafio: eles devem
criar uma landing page como portfólio para uma empresa de arquitetura."

Foram ao todo 5 etapas para a criação do produto final.

PRIMEIRA ETAPA:

- Criar um layout com base no protótipo disponibilizado pelo Figma. 

Comecei analizando bem o que foi disponibilizado e organizando o passo a passo para comecar a criar o front-end da aplicação HTML. Após isso, 
já comecei a desenvolver a página, pela seguinte ordem: 

- MENU SUPERIOR;
- MENU INFORMATIVO;
- MENU PRINCIPAL;
- FORMULÁRIO;

OBS: Seguindo ao máximo o que foi requisitado no protótipo da página.

SEGUNDA ETAPA:

- Integrar o formulário da página.

Utilizei o Sheet Monkey para realizar a integração do formulário da página com uma planilha do google onde as informações ficaram gravadas. 
Para isso, escrevi o seguinte bloco:

 <form action="https://api.sheetmonkey.io/form/bQzKgx2YVxzXcyRVeCgnvC" method="post">
            <input type="text" placeholder="Nome" name="Name" required><br><br>
            <input type="email" placeholder="Email" name="Email" required><br>
            <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time"/>
            <button type="submit">Fale Conosco</button><br>
        </form>
OBS: Foram pedidas no formulário apenas duas informações do usuário, o nome e email. Com a integração o nome, o email e a data/hora do preenchimento são enviadas e guardadas na planilha Google.

TERCEIRA ETAPA:

- Disponibiliar o projeto no Github

Antes de realizar a disponibilização, a pagina foi testada diversas vezes para garantir o funcionamento de tudo.


QUARTA ETAPA:

- Hospedar o site no Netlify

Utilizando o repositório do Github, o site foi hospedado no Netlify. Garantindo que todos, em qualquer lugar, tenham acesso à página.

QUINTA ETAPA:

- Preparar a documentação

Foram disponibilizados os links para o acesso à planilha e ao site onde aem questão(TOPO DA PÁGINA).

        

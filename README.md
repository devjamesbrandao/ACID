# ACID
Estudos sobre o conceito de ACID em transações realizadas em banco de dados

<p align="center">
    <img src="https://miro.medium.com/max/720/1*-Wx-fy3_UhMxsnOsbtwDsg.png" alt="Imagem ACID" title="Imagem ACID">
</p> 

<p><strong>ACID</strong> é um conceito que se refere às quatro propriedades de transação de um sistema de banco de dados: <strong>A</strong>tomicidade, <strong>C</strong>onsistência, <strong>I</strong>solamento e <strong>D</strong>urabilidade.</p>

<p><strong>Atomicidade:</strong> Em uma transação envolvendo duas ou mais partes de informações discretas, ou a transação será executada totalmente ou não será executada, garantindo assim que as transações sejam atômicas.</p>

<p><strong>Consistência:</strong> A transação cria um novo estado válido dos dados ou em caso de falha retorna todos os dados ao seu estado antes que a transação foi iniciada.</p>

<p><strong>Isolamento:</strong> Uma transação em andamento mas ainda não validada deve permanecer isolada de qualquer outra operação, ou seja, garantimos que a transação não será interferida por nenhuma outra transação concorrente.</p>

<p><strong>Durabilidade:</strong> Dados validados são registados pelo sistema de tal forma que mesmo no caso de uma falha e/ou reinício do sistema, os dados estão disponíveis em seu estado correto.</p>

# ` 🌐 Referências`
- <p>O conceito ACID: https://medium.com/@peretta.breno/propriedades-acid-em-banco-de-dados-b5e57f9904f0</p>

- <p>O que é ACID?: https://medium.com/opensanca/o-que-%C3%A9-acid-59b11a81e2c6</p>

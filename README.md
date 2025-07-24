## 📌 Atividade 01 - Games Online

Crie um banco de dados para um serviço de um **Games Online**.  
O nome do banco de dados deverá ser: `db_generation_game_online`.  
O sistema trabalhará com as informações dos personagens do jogo.  
O sistema terá 2 tabelas: `tb_personagens` e `tb_classes`, que estarão relacionadas.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a694c0f2-9e24-4f67-b842-ceec3cbb5c1f" width="572" height="126" />
</p>

### ✅ Boas Práticas

1. Crie a tabela `tb_classes` com pelo menos 2 atributos além da chave primária.  
2. Crie a tabela `tb_personagens` com 4 atributos além da chave primária.  
3. Crie a **foreign key** da tabela `tb_classes` na tabela `tb_personagens`.  
4. Insira 5 registros na tabela `tb_classes`.  
5. Insira 8 registros na tabela `tb_personagens`, vinculando à chave estrangeira.  
6. Faça um `SELECT` que retorne todos os personagens com poder de ataque > 2000.  
7. Faça um `SELECT` com personagens com poder de defesa entre 1000 e 2000.  
8. Faça um `SELECT` com `LIKE`, buscando personagens com a letra **C** no nome.  
9. Faça um `SELECT` com `INNER JOIN`, unindo `tb_personagens` e `tb_classes`.  
10. Faça um `SELECT` com `INNER JOIN` filtrando por uma classe específica (ex: Arqueiros).  
11. Salve todas as queries em um único script `.SQL` e envie para seu GitHub no repositório de banco de dados.

---

## 📌 Atividade 02 - Pizzaria

Crie um banco de dados para um serviço de uma **Pizzaria**.  
O nome do banco de dados deverá ser: `db_pizzaria_legal`.  
O sistema trabalhará com informações dos produtos comercializados pela empresa.  
O sistema terá 2 tabelas: `tb_pizzas` e `tb_categorias`, que deverão estar relacionadas.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3a15bf4c-e8d2-4dba-b153-1db2896e9d11" width="558" height="129" />
</p>

### ✅ Boas Práticas

1. Crie a tabela `tb_categorias` com pelo menos 2 atributos além da chave primária.  
2. Crie a tabela `tb_pizzas` com 4 atributos além da chave primária.  
3. Crie a **foreign key** da tabela `tb_categorias` na tabela `tb_pizzas`.  
4. Insira 5 registros na tabela `tb_categorias`.  
5. Insira 8 registros na tabela `tb_pizzas`, vinculando à chave estrangeira.  
6. Faça um `SELECT` que retorne todas as pizzas com valor > R$ 45,00.  
7. Faça um `SELECT` com pizzas entre R$ 50,00 e R$ 100,00.  
8. Faça um `SELECT` com `LIKE`, buscando pizzas com a letra **M** no nome.  
9. Faça um `SELECT` com `INNER JOIN`, unindo `tb_pizzas` e `tb_categorias`.  
10. Faça um `SELECT` com `INNER JOIN` filtrando por uma categoria específica (ex: Doces).  
11. Salve todas as queries em um único script `.SQL` e envie para seu GitHub no repositório de banco de dados.

---

## 📌 Atividade 03 - Farmácia

Crie um banco de dados para um serviço de uma **Farmácia**.  
O nome do banco de dados deverá ser: `db_farmacia_bem_estar`.  
O sistema trabalhará com informações dos produtos comercializados pela empresa.  
O sistema terá 2 tabelas: `tb_produtos` e `tb_categorias`, que deverão estar relacionadas.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b0b06ba7-437a-431c-8044-616282afef99" width="565" height="109" />
</p>

### ✅ Boas Práticas

1. Crie a tabela `tb_categorias` com pelo menos 2 atributos além da chave primária.  
2. Crie a tabela `tb_produtos` com 4 atributos além da chave primária.  
3. Crie a **foreign key** da tabela `tb_categorias` na tabela `tb_produtos`.  
4. Insira 5 registros na tabela `tb_categorias`.  
5. Insira 8 registros na tabela `tb_produtos`, vinculando à chave estrangeira.  
6. Faça um `SELECT` que retorne todos os produtos com valor > R$ 50,00.  
7. Faça um `SELECT` com produtos entre R$ 5,00 e R$ 60,00.  
8. Faça um `SELECT` com `LIKE`, buscando produtos com a letra **C** no nome.  
9. Faça um `SELECT` com `INNER JOIN`, unindo `tb_produtos` e `tb_categorias`.  
10. Faça um `SELECT` com `INNER JOIN` filtrando por uma categoria específica (ex: Cosméticos).  
11. Salve todas as queries em um único script `.SQL` e envie para seu GitHub no repositório de banco de dados.

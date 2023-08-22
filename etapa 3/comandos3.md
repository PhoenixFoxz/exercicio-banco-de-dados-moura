# Etapa 3

## Consulta mostrando os alunos que nasceram antes do ano de 2009

```SQL
SELECT nome "Alunos", nascimento "Data de Nascimento" FROM alunos WHERE nascimento <= "2009-01-01"
ORDER BY nascimento;
```

![Tabela contendo os Alunos que nasceram antes do ano de 2009](tabelaData.png)

## Consulta de calculo da média das notas de cada aluno mostrando com duas casas decimais.

```SQL
SELECT nome Alunos, CAST(((nota1 + nota2) / 2) AS DEC(6,2)) Média FROM alunos
```

![Tabela contendo a média de cada aluno](tabelaMedia.png)

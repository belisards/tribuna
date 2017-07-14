# -| Tribuna Eleitoral |-

[![auto-de-fe](doc/francisco_rizi-auto_de_fe.jpg)](https://upload.wikimedia.org/wikipedia/commons/2/28/Francisco_rizi-auto_de_fe.jpg)

----
<p align="center">
  (fase experimental: validando dados inconsistentes)
</p>

----
### O que é?

Esse projeto **corrige, integra, estrutura e otimiza as receitas brutas** da *Prestação de Contas do Tribunal Superior Eleitoral*, disponível no [Repositório de Dados Eleitorais](http://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais/), num Banco de Dados Relacional preparado para inquéritos, além de propor ferramentas abertas que facilitem sua relevante investigação por jornalistas, hackers e ativistas.

----

### Por quê?

Planilhas são inviáveis para relacionar informação nessa escala. Em 2014 foi necessário analisar os caóticos dados providos pelo TSE na pesquisa e apuração de **Jornalismo Investigativo** que resultou na matéria [As quatro irmãs](http://apublica.org/2014/06/as-quatro-irmas/);
> Negócios familiares, proximidade com governos, financiamento de campanhas e diversificação de atividades – da telefonia ao setor armamentício – compõem a história das gigantes Odebrecht, OAS, Camargo Corrêa e Andrade Gutierrez.

Porém, muitos *"furos"* e **indícios de corrupção e atos ilícitos** ainda podem ser evidenciados cruzando esses dados entre *Doadores, Candidatos e Partidos*, revelando - a princípio - os financiamentos e influências no Poder Público dos últimos 15 anos. Fatos ainda inexplorados e ocultos na *Política Brasileira* agora se tornam *acessíveis e apuráveis*.

Se um *Tribunal Eleitoral* é o lugar onde se administra justiça, garantindo a legitimidade e transparência do processo eleitoral, **o TSE peca** - o faz de forma obscura e grotesca. Voltemos a *Tribuna*, local elevado para espetáculos e debates públicos.

---

### Como?

O script **auditável** proposto [ilumina.sh](ilumina.sh) pega as fontes oficiais e estrutura o banco de dados relacional num processo automático que pode levar mais de 8 horas de processamento de dados. Ver a [Metodologia](doc/metodologia.md).

---

### Resultado
![modelo](doc/modelo.png)

=> Download do [dump](http://extrapolo.com/projeto/tse/tse2016.sql.tar.bz2) público final do database.

---

### Links

- [Dashboard](https://meta.mostre.me/public/dashboard/af26d09e-2994-4e39-8593-49e8a87fe5f5) básico com dados da Tribuna
- [Wiki](https://github.com/rafapolo/tribuna/wiki/SQL) de inquéritos básicos em [SQL](https://pt.wikipedia.org/wiki/SQL)
- [tse-monit](http://git.mostre.me/rafapolo/tse-monit) para monitorar mudanças
- [Mostre!me Eleições](https://mostre.me/eleicoes) subversão 0.1
---

Rafael Polo, Atenas 2017

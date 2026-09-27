# Redes Sociais para Criadores IA v6.2

Curso gratuito INEMA.CLUB no estilo OSWork v6.2: 18 aulas, 6 módulos, três pilares, pesquisa de dez referências, 33 aberturas originais, planejador de sete dias e uma publicação real feita pelo aluno. Estimativa: 10–14 horas, além da semana de acompanhamento.

Sistema Viral é o nome da proposta, não garantia de viralização. Bia e Nelson e o perfil Reuso de Bolso são fictícios. Dados de exemplo são identificados. Nenhum perfil social foi criado ou operado na produção deste material. O curso fornece leitura e exercícios, não videoaulas gravadas nem métricas reais de campanha.

Ilustrações criadas no recurso nativo de imagens do Codex, solicitado pelo usuário. A ferramenta não oferece seletor ou confirmação de versão 2.5. Nenhum gerador externo foi substituído.

Planejador local no navegador, exportação e importação de JSON. Não envia nem agenda publicações externas. Progresso de aula não comprova execução da atividade.

Reconstrução: python3 montar-apoio.py; python3 montar.py.

## English / Español

[English](https://inematds.github.io/curso-redes-sociais-ia/en/) · [Español](https://inematds.github.io/curso-redes-sociais-ia/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. Ilustrações originais compartilhadas; progresso e anotações separados por idioma.

Após montar o português, reaplique os catálogos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem não chama modelos nem redes. Mudanças na fonte PT exigem revisar os catálogos `i18n/`. O motor oficial `assets/curso.js` é preservado; a proteção de importação é gerada em `assets/curso-i18n.js` e nas edições traduzidas.

Evidências em `context/validacao-i18n.md`. Revisões por agentes são simuladas, não testes com alunos reais.

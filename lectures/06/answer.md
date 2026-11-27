# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：app.agent は search_materials、app.mcp_agent は glossary_search_glossary（どちらも1個）
- STEP 2 の [tool call]：glossary_search_glossary({'query': '3レベル'})
- STEP 3 の [tool call]：fetch_fetch({'url': 'https://raw.githubusercontent.com/matsuolab/lecture-ai-engineering-2026/main/lectures/06/problem.md'})
- STEP 4 の [tool call]：glossary_search_glossary({'query': '第2回'})
- 気づき・疑問：STEP 3 では fetch サーバーが problem.md を読み、その内容が宿題3レベルの回答に反映された。STEP 4 では AWS サーバーには接続できたが、モデルは AWS のツールではなく glossary サーバーのツールを使って答えた。サーバーを増やすとモデルに見えるツールが増え、入力トークンが増えることも分かった。

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎 / 実装 / 発展
- やったこと：
- 結果：
- 気づき・疑問：

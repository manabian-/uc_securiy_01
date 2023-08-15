# 概要

Databricks Unity Catalogのデータにアクセスするためのアクセス権限確認のためのノートブック群です。

## 前提事項

- アカウントレベルにて次のグループを作成して、それぞれのグループに所属したユーザーにて Databricks Workspace にログインしてセルを実行してください。
    - uc_test__uc_test_01__admin -> アカウント管理者グループ
    -　uc_test_all_read-> 権限付与対象者グループ

## 実行方法

`T01_adimin__uc_basic`の実行と`T01_user__uc_basic`の実行を、それぞれのセクションごとに、繰り返し行うことを想定しいてます。
# Log shipping from Managed Kubernetes to ClickHouse
## Создайте поток данных Yandex Data Streams
Выполнить [инструкцию по установке](https://cloud.yandex.ru/docs/data-streams/quickstart/create-stream)
## Создайте AWS-совместимые статические ключи доступа
Выполнить [инструкцию посозданию ключей] (https://cloud.yandex.ru/docs/iam/concepts/authorization/access-key)

* Замените в файле values.yaml значение: 
  ```
  ydsStream: xxxx.xx 
  ycApiKey:
      keyId: "xxxxx"
      accessKey: "yyyyy"
  ```
[см. полный список сценариев здесь... ](https://github.com/yandex-cloud/yc-architect-solution-library/tree/main/demos)


# Project Akhir

- Front-End Service: https://github.com/muhammadfajri-student-devs/notes-ui-serverless
- API Service: https://github.com/muhammadfajri-student-devs/notes-api-cdk

> **Note**
> Lihat [bagian catatan](#catatan-tambahan) untuk mengetahui lebih lanjut
> mengenai database

## Front-End Service

Stack:
- Typescript
- ReactJS
- Webpack
- Serverless Framework


## API Service

Stack:
- Typescript
- AWS Lambda
- AWS CDK
- DynamoDB (No-SQL key-value database)


## Catatan Tambahan
- Database sudah otomatis dibuat ketika API Service di deploy menggunakan AWS
  CDK
- Kode yang digunakan untuk mendefinisikan DynamoDB di AWS terdapat
  [disini](https://github.com/muhammadfajri-student-devs/notes-api-cdk/blob/main/lib/constructs/dynamodb-construct.ts)
- Kode yang digunakan untuk mendefinisikan tabel pada DynamoDB terdapat
  [disini](https://github.com/muhammadfajri-student-devs/notes-api-cdk/blob/main/lib/notes-api-cdk-stack.ts#L60)
- Kode yang digunakan untuk mengonfigurasi tabel dan database DynamoDB terdapat
  [disini (stage development)](https://github.com/muhammadfajri-student-devs/notes-api-cdk/blob/main/config/dev-stage-props.ts#L21) atau [disini (stage production)](https://github.com/muhammadfajri-student-devs/notes-api-cdk/blob/main/config/prod-stage-props.ts#L21)

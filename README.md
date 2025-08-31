# AWS-Lab-Lambda

## Evidências

<details>
    <summary>Policy e Role IAM</summary>
    <p>Crição da Policy p/ permitir que o lambda finalize instâncias EC2.</p>
    <img src="/assets/policy-creation.png">
    <br>
    <img src="/assets/created-policy.png">
    <br>
    <p>Criação da Role p/ associar a função Lambda.</p>
    <img src="/assets/role-creation.png">
</details>

<details>
    <summary>Lambda Function</summary>
    <p>Função Lambda para finalizar instâncias EC2.</p>
    <img src="/assets/created-lambda.png">
</details>

<details>
    <summary>EventBridge Lambda Trigger</summary>
    <p>EventBridge Trigger p/ executar a função lambda a cada 5 minutos</p>
    <img src="/assets/lambda-trigger-creation.png">
</details>

<details>
    <summary>CloudWatch Logs</summary>
    <p>Logs p/ observar cada execução da função lambda</p>
    <img src="/assets/CloudWatch-logs.png">
</details>

## Agradecimentos
Agradeço ao professor Matheus Philippo e toda equipe da [Escola da Nuvem](https://escoladanuvem.org/).
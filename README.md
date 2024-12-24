1. terraform init

2. personal.auto.tfvars

3. "result": "dnzqyzSnYMm3jr8s"

4. Отсутствие наименования у resource "docker_image", значение переменной name resource "docker_container" "1nginx" неправильно задано.

5. ![Alt text](https://github.com/RuslanArestov/Introduction-to-Terraform/blob/master/images/5.jpg)

6. Ключ -auto-approve позвояляет автоматизировать процеес запуска инфраструктуры. Опасность: специалист не видит изменения, которые применяются в инфраструктуре.

![Alt text](https://github.com/RuslanArestov/Introduction-to-Terraform/blob/images/master/6.jpg)

7. ```{
  "version": 4,
  "terraform_version": "1.10.2",
  "serial": 11,
  "lineage": "197c3d45-cd96-30d1-b80f-42dc1a1b2e59",
  "outputs": {},
  "resources": [],
  "check_results": null
}```

8. Сохранился их-за параметра keep_locally = true

keep_locally (Boolean) If true, then the Docker image won't be deleted on destroy operation. If this is false, it will delete the image from the docker local storage on destroy operation.
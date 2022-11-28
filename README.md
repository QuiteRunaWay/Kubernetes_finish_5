# Домашнее задание к занятию "14.5 SecurityContext, NetworkPolicies"

## Задача 1: Рассмотрите пример 14.5/example-security-context.yml

Создайте модуль

```
kubectl apply -f 14.5/example-security-context.yml
```

Проверьте установленные настройки внутри контейнера

```
kubectl logs security-context-demo
uid=1000 gid=3000 groups=3000
```

## Ответ: 

![image](https://user-images.githubusercontent.com/92969676/204327595-88ca3344-0cbf-4e39-94c0-2c0eebafbc43.png)

Проверяем и убеждаемся, что настройки дейстивтельно такие, как были заданы:

![image](https://user-images.githubusercontent.com/92969676/204328221-37ac8142-ba0f-4db1-9611-ce8d3f4b6659.png)

![image](https://user-images.githubusercontent.com/92969676/204327882-7a7a71ac-2764-43ba-8502-653ae0827778.png)

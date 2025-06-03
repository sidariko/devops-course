# Redis StatefulSet

## Мета
Створення Redis-кластера з двома репліками, що використовує стабільні імена та постійні томи для зберігання даних.

## Кроки
1. Створення PersistentVolumeClaim (PVC).
2. Створення StatefulSet для Redis.
3. Створення Service для Redis.
4. Перевірка роботи.

## Конфігураційні файли
- `redis-pvc.yaml`
- `redis-statefulset.yaml`
- `redis-service.yaml`

## Перевірка
- `kubectl get pods`
- `kubectl exec -it redis-0 -- redis-cli`
- `kubectl exec -it redis-1 -- redis-cli`

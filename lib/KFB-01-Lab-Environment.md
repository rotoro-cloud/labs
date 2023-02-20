Question:
  - Сколько нод являются участниками кластера?

Checks:
  - kubectl get no
 
---

Question:
  - Какая версия Кубернетес запущена на нодах?
  
Checks:
  - kubectl get no

---

Question:
  - Какой тип и версия операционной системы, на которой запущены ноды Kubernetes?
  
Checks:
  - kubectl get nodes -o wide

# паттерны проектирования это коммуникация между разработчиками.

для того чтобы решить какую то задачу.
сэкономить время и решить задачу. все время потратил на алгоритм сортировки.


https://habr.com/en/post/210288/
где то шаблон где подходит,  spa , mvc,



1.CQS не CQRS (CQRS использует 2 дата стора)
CQRS при команде уведомляет другие дата стор что произошли изменения
это шаблон проектирования Meaditor (Наблюдатель)

2.EF core использует паттерн стратегия в MS SQL, oracle
но Майки его обозвали Provider design pattern

3.Singleton это как программный так и архитектурный шаблон.
он может применяться например при IdistributedCache или использования Redis для хранения сессий пользователя !

4.Iterator паттерн может реализовывать с помощью dotnet интерфейсов IEnumerator and IEnumerables.

5.Facade это когда есть куча подсистем  
Пример со смартфоном.
![alt text](
https://www.codeproject.com/KB/architecture/481297/myFacade.jpg)

![alt text](https://hsto.org/storage3/432/f5c/b4b/432f5cb4b5387312374fc36ba088f53e.png)


![alt text](https://hsto.org/storage3/d8e/61e/396/d8e61e3961a76a749eb3b8bfe07c3bd7.png)

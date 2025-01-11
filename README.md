## 1. Golang

### 1.1 Базовые вопросы
Здесь собраны основные вопросы, которые помогут понять фундаментальные концепции языка Go.

- **Типы данных**
  - Описание базовых типов данных в Go: int, float, string, bool, а также составные типы (массивы, слайсы, структуры, мапы).
- **Что такое type switch**
  - Использование `type switch` для определения типа интерфейса и выполнения соответствующих действий.
- **Что такое интерфейсы**
  - Интерфейсы в Go: как они работают, зачем нужны и как их использовать.
- **Зачем нужен defer**
  - Ключевое слово `defer`: отложенное выполнение функций, порядок вызова и практическое применение.
- **Что такое panic/recover?**
  - Обработка ошибок с помощью `panic` и `recover`: как использовать и когда это уместно.
- **Как передаются данные в Go**
  - Передача данных по значению и по ссылке: в чем разница и как это влияет на производительность.

---

### 1.2 Вопросы сложнее
Эти вопросы требуют более глубокого понимания языка и его внутренней работы.

- **Что такое рефлексия и пакет reflect**
  - Рефлексия в Go: как использовать пакет `reflect` для анализа типов и значений во время выполнения.
- **Как в Go организовано наследование/инкапсуляция**
  - Отсутствие классического наследования в Go: композиция, встраивание и интерфейсы как альтернатива.
- **Типы синхронизации**
  - Примитивы синхронизации: мьютексы, каналы, `sync.WaitGroup`, `sync.Once` и другие.
- **Что такое горутина / GMP?**
  - Горутины: легковесные потоки в Go. Модель GMP (Goroutine, M, P) и как она работает.
- **Что такое дедлок/фрилок**
  - Дедлоки и фрилоки: причины возникновения и способы предотвращения.
- **Немного про heap/stack**
  - Управление памятью в Go: что хранится в heap, а что в stack, и как это влияет на производительность.
- **Как сообщить компилятору, что наш тип реализует интерфейс?**
  - Реализация интерфейсов в Go: как компилятор проверяет, что тип удовлетворяет интерфейсу.

---

### 1.3 Вопросы с расширенным ответом
Эти вопросы требуют глубокого понимания внутренней работы Go и его runtime.

- **Как устроена мапа?**
  - Внутренняя структура мапы в Go: хэш-таблицы, коллизии и производительность.
- **Как устроен слайс?**
  - Слайсы в Go: внутреннее представление, capacity, length и операции (append, copy).
- **Как устроены каналы?**
  - Каналы в Go: буферизованные и небуферизованные, как они работают на уровне runtime.
- **Профилирование pprof?**
  - Использование пакета `pprof` для профилирования производительности: CPU, memory, блокировки и горутины.
- **Как устроен шедулер?**
  - Шедулер Go: как он управляет горутинами, планирование и приоритеты.

---

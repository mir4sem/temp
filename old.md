### Классы выпусков дистрибутивов Debian
- Stable
- Testing
- Unstable
- Experimental

**Среда окружения** - набор параметров и настроек, определяют характеристики программного обеспечения или UI, включают в себя:

1. Переменные среды: Это значения, которые определяют различные параметры и настройки. Примеры переменных среды пути к исполняемым файлам, настройки языка, временные директории и другие параметры.
2. Языковые настройки: Языковые настройки включают в себя параметры, связанные с форматированием даты и времени, валютой, числовыми форматами и т.д.
3. Опции запуска программ: Это параметры, которые передаются программе при её запуске и определяют её поведение. Например, опции командной строки могут указывать программе, какие файлы обрабатывать, какие функции включать или отключать и т.д.
4. Библиотеки и зависимости: Это компоненты, необходимые для работы программы, такие как динамические библиотеки, общие ресурсы и другие зависимости, информация о расположении и доступности этих компонентов.
5. Конфигурационные файлы: Это файлы, которые содержат настройки программ и системных компонентов.
6. Параметры безопасности, права доступа, настройки сети и т.д.

### Основные переменные среды
- Переменная PATH содержит список каталогов, в которых операционная система ищет исполняемые файлы команд. При вводе команды Linux проверяет папку в PATH, чтобы найти файл.
- Переменная HOME определяет домашний каталог пользователя
- LANG и LC_  переменные определяют язык и локализацию,
- PS1 определяет формат приглашения командной строки (промпта)
- EDITOR программа по умолчанию для редактирования текста.
- TERM определяет тип терминала
- SHELL определяет командный интерпретатор

### Ярус
Слои, уровни, разделенеи системы, абстрактные концепции

- Аппаратный ярус: физические компоненты компьютера
- Ядро ОС: управляет аппаратными ресурсами, интерфейсы, памятью, процессорами
- Пользовательские проги: драйверы, и др.

### Регулярные выражения
ДКА, НДА, рекурсивный спуск

### Непрерывная доставка
Continuous Delivery, CD - это методология разработки программного обеспечения, которая направлена на автоматизацию процесса доставки приложений в производственную среду с минимальными ручными вмешательствами. 

- Автоматизация сборки
- Автоматизация тестирования
- Контроль версий
- Автоматизация развертывания

### Н Интеграция
Методология разработки программного обеспечения, которая направлена на автоматизацию процесса объединения (интеграции) изменений в коде всех разработчиков в общий репозиторий, а также на выполнение автоматизированных тестов для обеспечения работоспособности приложения после каждого изменения.

### Образ контейнера
Шаблон, содержащий все необходимые компоненты и настройки для запуска контейнера.

- операционную систему
- библиотеки
- приложения

### 2 состояния
- Состояние образа до запуска (ISO)
- Состояние контейнера после запуска

### Контейнерный движок
Управляет созданием, запуском и управлением контейнерами. 

### Контейнерный хост
Компьютер или сервер, на котором работает контейнерный движок и который используется для запуска и управления контейнерами. 

управление ресурсами, изоляция контейнеров

### Сервер реестра
Централизованное хранилище для контейнерных образов. Он обеспечивает доступ к образам контейнеров

### Docker
Docker-демон - это фоновый процесс, который управляет созданием, запуском и управлением контейнерами

Docker-клиент - это интерфейс командной строки или графический интерфейс,

Докер-образ шаблон для контейнера Docker.

Докер-реестр - централизованное хранилище для образов

### Пространство имен в системе Docker
изоляцию процессов и ресурсов между контейнерами.

- Пространство имен PID (PID Namespace)
- Пространство имен сети (Network Namespace)
- Пространство имен файловой системы (Mount Namespace)
- Пространство имен IPC (IPC Namespace):
- Пространство имен UTS (UTS Namespace):
- Пространство имен пользователя (User Namespace)

### Конфигурационное управление
установку, настройку, обновление и мониторинг конфигураций

### Компоненты ОС
- Ядро
- Драйверы
- Оболочка
- Службы

Конфигурационное управление — процесс управления состоянием системы, программного обеспечения, идентификация и документирование конфигурации, контроль изменений, аудит и верификацию состояния конфигурации. Цели - обеспечение целостности и доступности конфигурации системы, управление изменениями, соблюдение требований и стандартов, повышение эффективности и улучшение процессов разработки и сопровождения.

Операционная система - управляет аппаратными и программными ресурсами компьютера и обеспечивает пользователям среду выполнения приложений. Основные задачи:
- управление ресурсами ПК (устройствами ввода-вывода)
- обеспечение защиты данных
- управление процессами и потоками
- обеспечение интерфейсов
- управление файловой системой
- многозадачность и многопользовательских сред.

Основные функции операционной системы включают:
1. Управление процессами: управление созданием, выполнением и завершением процессов, а также распределение ресурсов между ними.
2. Управление памятью: управление выделением и освобождением оперативной памяти, виртуальная память, обеспечение защиты памяти от несанкционированного доступа.
3. Управление устройствами: обеспечение взаимодействия операционной системы с аппаратными устройствами компьютера.
4. Управление файловой системой: организация и управление файлами и каталогами, обеспечение доступа к данным на устройствах хранения.
5. Обеспечение интерфейсов для взаимодействия: предоставление пользователю графического или командного интерфейса для работы с системой.

Дополнительные функции операционной системы могут включать:

1. Управление сетью: поддержка сетевых протоколов и механизмов для обмена данными между компьютерами.
2. Управление безопасностью: обеспечение защиты данных и системы от несанкционированного доступа и вредоносных программ.
3. Управление энергопотреблением: оптимизация работы системы с целью снижения энергопотребления и увеличения срока автономной работы устройств.
4. Мониторинг и отладка: предоставление инструментов для отслеживания и анализа работы системы, выявление и устранение ошибок и неисправностей.

Операционные системы применяются на широком спектре вычислительных устройств, включая персональные компьютеры, серверы, мобильные устройства, встроенные системы и суперкомпьютеры.

Конфигурационное управление обычно включает в себя следующие задачи:

1. **Идентификация конфигурации:** Определение компонентов, которые составляют конфигурацию системы или продукта, и их связей друг с другом.

2. **Документирование конфигурации:** Создание и поддержание документации, описывающей конфигурацию системы или продукта, включая спецификации, версии компонентов, зависимости и другую информацию.

3. **Контроль изменений:** Управление изменениями в конфигурации, включая процесс запроса на изменение, оценку влияния изменения, утверждение изменения, реализацию и тестирование изменений, а также регистрацию и анализ результатов.

4. **Аудит и верификация конфигурации:** Проверка текущего состояния конфигурации на соответствие документированным требованиям и стандартам, а также проведение аудитов для выявления и устранения несоответствий.

Операционная система, помимо основных функций, также может выполнять ряд дополнительных задач:

1. **Управление вводом-выводом:** Контроль доступа к устройствам ввода-вывода, буферизация данных, оптимизация передачи данных между устройствами и процессором.

2. **Управление энергопотреблением:** Механизмы оптимизации работы процессора и других компонентов для снижения энергопотребления и увеличения срока автономной работы устройства.

3. **Управление планированием задач:** Определение порядка выполнения задач и распределение ресурсов между ними с целью оптимизации производительности и уменьшения времени ожидания.

4. **Управление виртуализацией:** Предоставление механизмов для создания и управления виртуальными окружениями, что позволяет запускать несколько изолированных экземпляров операционной системы на одном физическом компьютере.

Область применения операционных систем включает:

1. **Персональные компьютеры:** Операционные системы, такие как Windows, macOS и Linux, широко используются на домашних и офисных компьютерах для выполнения различных задач.

2. **Серверы:** Операционные системы серверов, такие как Windows Server, Linux и UNIX, предназначены для обеспечения работы сетевых сервисов и приложений на серверном оборудовании.

3. **Мобильные устройства:** Операционные системы для мобильных устройств, такие как iOS и Android, предоставляют среду выполнения для мобильных приложений и обеспечивают взаимодействие с аппаратными компонентами

---

Файловая система (File System) — это метод организации и хранения данных на устройствах хранения, таких как жесткие диски, флэш-накопители, оптические диски и другие. Файловая система определяет структуру данных, доступные операции и способы управления файлами и каталогами.

Основные задачи файловой системы:

1. **Управление файлами и каталогами:** Файловая система позволяет создавать, удалять, перемещать, копировать и переименовывать файлы и каталоги.

2. **Организация пространства на диске:** Файловая система определяет способ размещения файлов на устройстве хранения, управляет свободным и занятым пространством на диске, а также обеспечивает защиту данных от повреждений.

3. **Поддержка доступа к данным:** Файловая система обеспечивает доступ к данным для чтения и записи, контролирует права доступа пользователей и групп к файлам и каталогам, а также обеспечивает защиту данных с помощью механизмов аутентификации и авторизации.

Виды файловых систем:

1. **Локальные файловые системы:** Эти файловые системы предназначены для использования на отдельных компьютерах или серверах и обеспечивают хранение и доступ к данным на локальных устройствах хранения. Примеры включают NTFS (Windows), ext4 (Linux), HFS+ (macOS) и APFS (новая файловая система для macOS и iOS).

2. **Сетевые файловые системы:** Эти файловые системы предназначены для доступа к данным на удаленных серверах через сеть. Они позволяют пользователям монтировать удаленные ресурсы как локальные устройства хранения. Примеры включают NFS (Network File System), SMB (Server Message Block) и AFP (Apple Filing Protocol).

3. **Журналирующие файловые системы:** Эти файловые системы ведут журнал изменений, что позволяет восстанавливать данные после сбоев или аварийного отключения питания. Журналирование уменьшает риск потери данных и повреждения файловой системы. Примеры включают NTFS (Windows), ext4 (Linux) и HFS+ (macOS).

4. **Файловые системы для встроенных устройств:** Эти файловые системы оптимизированы для использования в ограниченных встроенных системах, таких как мобильные устройства, системы хранения данных и встроенные устройства IoT. Примеры включают YAFFS (Yet Another Flash File System), JFFS2 (Journaling Flash File System 2) и UBIFS (Unsorted Block Image File System).

Одноуровневая файловая система и иерархическая файловая система отличаются по структуре организации файлов и каталогов.

1. **Одноуровневая файловая система:**

   В одноуровневой файловой системе все файлы хранятся в едином каталоге без подразделения на подкаталоги. Это означает, что каждый файл имеет уникальное имя в пределах всей файловой системы. Такие файловые системы просты в реализации и управлении, но могут столкнуться с ограничениями, когда число файлов становится слишком велико, что затрудняет поиск и организацию данных.

2. **Иерархическая файловая система:**

   В иерархической файловой системе файлы и каталоги организованы в виде древовидной структуры, где каждый каталог может содержать подкаталоги и файлы. Верхний уровень дерева представляет собой корневой каталог, который может содержать другие каталоги, и так далее. Каждый элемент в такой структуре (файл или каталог) имеет уникальный путь к нему от корневого каталога.

Иерархическая файловая система имеет ряд преимуществ по сравнению с одноуровневой:

- **Структурированность:** Иерархическая структура обеспечивает более удобное и организованное размещение файлов и каталогов, что облегчает их поиск и управление.

- **Удобство навигации:** Пользователи могут использовать иерархическую структуру для быстрого доступа к нужным файлам и каталогам, используя пути к ним.

- **Масштабируемость:** Иерархическая файловая система лучше масштабируется при увеличении количества файлов и каталогов, поскольку она позволяет организовать их в более удобной форме.

Примеры иерархических файловых систем включают NTFS и FAT (для Windows), ext4 (для Linux), HFS+ и APFS (для macOS).

-------

Проприетарное программное обеспечение (ППО) — это программное обеспечение, права на которое контролируются правообладателем или компанией-разработчиком, и доступ к его исходному коду ограничен или отсутствует. Владелец программного обеспечения устанавливает условия использования, распространения и модификации программы.

Особенности распространения и использования проприетарного программного обеспечения:

1. **Лицензионное соглашение:** Пользователь получает право использовать программное обеспечение только после того, как он согласится с условиями лицензионного соглашения, которое обычно определяет права и обязанности пользователя, ограничения на использование, срок действия лицензии и другие условия.

2. **Ограничения на распространение:** Пользователь не имеет права передавать программное обеспечение третьим лицам без разрешения правообладателя. Распространение программного обеспечения без соответствующей лицензии может быть нарушением авторских прав.

3. **Отсутствие доступа к исходному коду:** В отличие от открытого программного обеспечения (Open Source), у проприетарного программного обеспечения обычно отсутствует доступ к исходному коду, что ограничивает возможности пользователей по его модификации и адаптации под свои нужды.

4. **Ограничения по использованию:** Правообладатель может устанавливать различные ограничения на использование программного обеспечения, такие как ограничения на количество устройств, на которых можно установить программу, или ограничения на тип использования (например, для коммерческих целей или для личного пользования).

5. **Поддержка и обновления:** Проприетарное программное обеспечение часто предоставляется сопровождающими услугами, такими как техническая поддержка, обновления и исправления ошибок. Пользователь может получать доступ к обновлениям только в рамках условий лицензионного соглашения.

Проприетарное программное обеспечение может использоваться в различных сферах, включая коммерческое программное обеспечение, игровую индустрию, медицинские приложения, корпоративные системы и другие области, где важны защита интеллектуальной собственности и контроль над продуктом.

Свободное программное обеспечение (СПО) — это программное обеспечение, которое распространяется с открытым исходным кодом и предоставляет пользователям право использовать, изучать, изменять и распространять его в соответствии с условиями определенной лицензии, которая обеспечивает свободу и открытость программного продукта.

Особенности распространения и использования свободного программного обеспечения:

1. **Свобода распространения:** Свободная лицензия позволяет пользователям свободно распространять программное обеспечение без ограничений, включая передачу его другим пользователям, изменение исходного кода и даже продажу программы (при условии соблюдения условий лицензии).

2. **Свобода использования:** Пользователи имеют право использовать свободное программное обеспечение для любых целей, включая коммерческое использование, обучение, научные и исследовательские цели, без необходимости получения разрешения или оплаты лицензионных сборов.

3. **Свобода изучения:** Пользователи имеют право изучать и анализировать исходный код программного обеспечения, что позволяет им лучше понимать его работу, исправлять ошибки и улучшать программу в соответствии с их потребностями.

4. **Свобода модификации:** Пользователи имеют право вносить изменения в исходный код свободного программного обеспечения, чтобы адаптировать его под свои потребности или улучшить его функциональность. Это позволяет сообществу разработчиков совместно сотрудничать над улучшением программы.

5. **Открытость сообщества:** Свободное программное обеспечение обычно разрабатывается сообществом разработчиков и пользователей, которые активно обмениваются знаниями, идеями и кодом через открытые форумы, списки рассылки, системы управления версиями и другие средства связи.

Примеры свободного программного обеспечения включают операционные системы Linux и FreeBSD, офисные пакеты LibreOffice и Apache OpenOffice, веб-сервер Apache HTTP Server, браузер Mozilla Firefox и многие другие программы и инструменты, которые доступны под свободными лицензиями, такими как GNU General Public License (GPL), MIT License, BSD License и др.

-------

Лицензия GNU General Public License (GNU GPL) — это одна из наиболее известных и широко используемых лицензий для свободного программного обеспечения. Она была разработана Фондом Свободного Программного Обеспечения (Free Software Foundation) и предоставляет пользователю широкие права на использование, модификацию и распространение программного обеспечения, защищая при этом свободу и открытость исходного кода.

Основные принципы GNU GPL включают:

1. **Свобода использования:** Пользователи имеют право использовать программное обеспечение, либо как есть, либо в составе других программ, для любых целей, включая коммерческое использование.

2. **Свобода изучения и изменения:** GNU GPL обязывает предоставлять исходный код программы, а также любые изменения и дополнения к нему, при распространении программы или ее модификации. Это дает пользователям возможность изучать и анализировать исходный код, вносить изменения и адаптировать программу под свои потребности.

3. **Свобода распространения:** GNU GPL позволяет свободно распространять программное обеспечение, включая его копирование, передачу и продажу, при условии соблюдения условий лицензии.

4. **Сохранение свободы:** GNU GPL содержит механизмы, которые обеспечивают сохранение свободы программного обеспечения и предотвращают его закрытие или приватизацию.

Основные версии GNU GPL включают GPL версии 1, 2 и 3. Каждая версия лицензии включает свои особенности и дополнения, направленные на адаптацию к современным требованиям и изменениям в области свободного программного обеспечения.

Лицензия GNU GPL также содержит условия о совместимости с другими лицензиями, а также о правах и обязанностях пользователей и разработчиков программного обеспечения. Она является одной из ключевых составляющих инфраструктуры свободного программного обеспечения и играет важную роль в развитии и поддержке открытых исходных кодовых проектов.

----------

Стандарт POSIX (Portable Operating System Interface) - это набор стандартов, разработанных IEEE (Institute of Electrical and Electronics Engineers), определяющих интерфейсы между операционной системой и прикладным программным обеспечением. Он был создан с целью обеспечения совместимости между различными UNIX-подобными операционными системами и повышения их переносимости.

Основные задачи стандарта POSIX включают:

1. **Обеспечение переносимости программного обеспечения:** POSIX определяет интерфейсы для различных функций операционной системы, таких как ввод-вывод, работа с файлами, управление процессами и потоками, сетевое взаимодействие и другие, что обеспечивает совместимость программ между различными UNIX-подобными системами.

2. **Унификация API:** POSIX стандартизирует интерфейсы программирования приложений (API), что позволяет разработчикам писать программное обеспечение, используя общие методы и функции, которые будут работать на всех совместимых с POSIX операционных системах.

3. **Обеспечение совместимости с UNIX:** POSIX основан на стандартах и интерфейсах, унаследованных от операционной системы UNIX, что позволяет создавать и запускать программы, написанные для UNIX, на системах, совместимых с POSIX.

4. **Повышение качества и надежности программного обеспечения:** Стандарт POSIX включает в себя требования к функциональности и поведению операционной системы, что способствует созданию более надежных и качественных программных продуктов.

5. **Стимулирование инноваций и развития:** Стандарт POSIX является основой для разработки новых технологий и стандартов в области операционных систем, сетевых технологий и программирования, что способствует развитию индустрии информационных технологий.

Стандарт POSIX включает в себя несколько частей, включая POSIX.1 (базовый стандарт), POSIX.2 (командный интерфейс), POSIX.4 (расширенные возможности реального времени), POSIX.1003.1 (стандарт C), POSIX.1003.2 (шелл-скриптинг), и другие. Каждая часть стандарта определяет конкретные интерфейсы и функциональность, которые должны быть реализованы в соответствии с POSIX-совместимыми операционными системами.

1. **POSIX.1 (базовый стандарт):**
   - POSIX.1 определяет базовые интерфейсы системных вызовов и библиотечных функций для разработки приложений в UNIX-подобных операционных системах.
   - Этот стандарт включает в себя основные компоненты операционной системы, такие как управление процессами, управление файлами и каталогами, работу с устройствами ввода-вывода, управление сигналами и другие функции.
   - POSIX.1 обеспечивает переносимость приложений между различными UNIX-подобными системами, так как он стандартизирует основные системные вызовы и библиотечные функции.

2. **POSIX.2 (командный интерфейс):**
   - POSIX.2 определяет интерфейс командной строки для взаимодействия пользователя с операционной системой через командную оболочку (shell).
   - Этот стандарт включает в себя команды, аргументы командной строки, переменные окружения, синтаксис командной строки и другие элементы, необходимые для работы с командной оболочкой и выполнения команд в UNIX-подобных системах.
   - POSIX.2 также определяет стандартные потоки ввода, вывода и ошибок для командной строки.

3. **POSIX.4 (расширенные возможности реального времени):**
   - POSIX.4 определяет расширенные возможности для работы с реальным временем в операционных системах.
   - Этот стандарт включает в себя функции и интерфейсы для управления задачами в реальном времени, обработки сигналов в реальном времени, синхронизации событий, управления приоритетами задач и другие возможности, необходимые для разработки реального времени приложений.

4. **POSIX.1003.1 (стандарт C):**
   - POSIX.1003.1 определяет стандарт языка программирования Си (C) для UNIX-подобных операционных систем.
   - Этот стандарт включает в себя спецификацию стандартной библиотеки языка Си, включая функции ввода-вывода, математические функции, функции работы со строками, управление памятью и другие элементы.
   - POSIX.1003.1 обеспечивает переносимость и совместимость программ на языке Си между различными UNIX-подобными операционными системами.

5. **POSIX.1003.2 (шелл-скриптинг):**
   - POSIX.1003.2 определяет стандартный язык для написания скриптов командной оболочки (shell scripts) в UNIX-подобных операционных системах.
   - Этот стандарт включает в себя синтаксис, семантику и стандартные команды для написания скриптов, которые могут выполняться командной оболочкой.
   - POSIX.1003.2 обеспечивает переносимость и совместимость скриптов между различными реализациями командных оболочек в UNIX-подобных системах.

------------------

Реализация графического интерфейса в операционной системе Linux осуществляется через использование X Window System, также известного как - **X11**. X11 является стандартом для графического пользовательского интерфейса в UNIX-подобных операционных системах, включая Linux.

Основные компоненты X Window System:

1. **X сервер (X server):** X сервер является основным компонентом, который управляет отображением графики и взаимодействием с аппаратурой. Он отвечает за рисование окон, обработку ввода с клавиатуры и мыши, а также передачу графических данных между клиентскими приложениями и аппаратурой.

2. **X клиенты (X clients):** X клиенты - это приложения, которые запускаются на операционной системе Linux и используют графический интерфейс. Они отправляют запросы на отображение графики и управление окнами на X сервер, который затем выполняет эти запросы.

3. **Window Manager:** Window Manager (менеджер окон) - это компонент, который отвечает за оформление и управление окнами приложений на экране. Window Manager обеспечивает функции, такие как изменение размеров окон, перемещение окон по экрану, а также управление расположением окон и рабочих столов.

4. **Desktop Environment:** Desktop Environment (рабочее окружение) - это комплексный набор приложений, включая Window Manager, файловый менеджер, панели задач и другие инструменты, предоставляющие пользователю полноценное рабочее окружение с графическим интерфейсом.

Программы, запускаемые в графическом режиме на Linux, общаются с X сервером через специальный протокол X Window System Protocol. X сервер затем рисует графические элементы на экране и обрабатывает пользовательский ввод.

Существуют различные реализации X сервера для Linux, такие как X.Org Server и Wayland. X.Org Server является наиболее широко используемым X сервером в сообществе Linux и обеспечивает основную инфраструктуру для работы графического интерфейса на большинстве дистрибутивов Linux.

-------------------

Конфигурационное управление (Configuration Management) - это процесс управления изменениями в различных элементах проекта или продукта, таких как программное обеспечение, аппаратное обеспечение, документация, данные и другие составляющие. Целью конфигурационного управления является обеспечение целостности, надежности и управляемости продукта или проекта на всех этапах его жизненного цикла.

Процедуры управления конфигурацией включают в себя следующие этапы:

1. **Идентификация конфигурации:** В этом этапе определяются элементы конфигурации, которые подлежат управлению. Это может включать программное обеспечение, документацию, аппаратное обеспечение, конфигурационные файлы, базы данных и другие составляющие продукта или проекта.

2. **Управление конфигурационной информацией:** Важной частью конфигурационного управления является управление информацией о состоянии и изменениях в конфигурации. Это включает в себя ведение журналов изменений, регистрацию версий, отслеживание зависимостей между элементами конфигурации и другие аспекты управления информацией.

3. **Контроль версий:** Контроль версий позволяет отслеживать изменения в элементах конфигурации и восстанавливать предыдущие версии в случае необходимости. Это обеспечивает сохранность данных и позволяет управлять изменениями в продукте или проекте.

4. **Конфигурационный аудит:** В процессе конфигурационного аудита проверяется соответствие текущего состояния конфигурации установленным стандартам и требованиям. Это помогает выявить возможные расхождения и проблемы в управлении конфигурацией.

5. **Управление изменениями:** Управление изменениями включает в себя процессы управления запросами на изменение, оценку влияния изменений, утверждение и реализацию изменений, а также оценку и контроль их эффектов.

6. **Резервное копирование и восстановление:** Регулярное резервное копирование данных и возможность восстановления предыдущих версий элементов конфигурации являются важной частью процесса управления конфигурацией.

------------

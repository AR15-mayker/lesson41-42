# lesson41-42
### параграф 41
### Попов георгий
Вопросы и задания  
1. Что такое машинный код?
  
   Машинный код — это низкоуровневый код, который непосредственно понимает процессор. Он представлен в двоичном формате и состоит из инструкций, которые выполняет аппаратное обеспечение.

2. Зачем нужны системы программирования? Можно ли обходиться без них?  

   Системы программирования обеспечивают разработчикам инструменты для написания, компиляции и отладки программ. Без них программирование было бы крайне сложным и времязатратным процессом.

3. Что такое язык ассемблера? Почему он называется машинно-ориентированным?  

   Язык ассемблера — это низкоуровневый язык программирования, который соответствует машинному коду. Он называется машинно-ориентированным, потому что его инструкции напрямую соответствуют архитектуре конкретного процессора.

4. Что такое язык программирования высокого уровня?  

   Язык программирования высокого уровня — это язык, который позволяет разработчикам писать код, близкий к человеческому языку и далекому от машинных инструкций. Это облегчает процесс написания и понимания программ.

5. Как можно разделить языки программирования по области применения?  

   Языки программирования можно разделить на системные (например, C, C++), прикладные (например, Python, Java), специализированные (например, SQL для работы с базами данных) и скриптовые языки (например, JavaScript).

6. Зачем нужен транслятор?  

Транслятор (компилятор или интерпретатор) необходим для преобразования кода, написанного на высокоуровневом языке, в машинный код, чтобы его мог выполнить процессор.

7. Какие два типа трансляторов вы знаете? В чём их достоинства и недостатки?  
  
   - Компиляторы: преобразуют весь код сразу, что позволяет генерировать оптимизированный машинный код, но требует времени на полную компиляцию.  
   - Интерпретаторы: выполняют код построчно, что позволяет сразу видеть результаты, но может быть медленнее из-за постоянного перевода.

8. Какие программы входят в системы программирования?  
 
   В системы программирования входят текстовые редакторы, компиляторы, интерпретаторы, отладчики, профилировщики и средства управления версиями.

9. Зачем нужен компоновщик?  

   Компоновщик необходим для объединения различных модулей программы в единый исполняемый файл, а также для разрешения ссылок между ними.

10. Что такое отладчик? Перечислите возможности отладчиков.  
  
    Отладчик — это инструмент для поиска и исправления ошибок в программах. Возможности отладчиков включают установку точек останова, просмотр значений переменных, пошаговое выполнение и анализ стека вызовов.

11. Что такое профилировщик? Зачем он нужен?  
  
    Профилировщик — это инструмент, который помогает анализировать производительность программы. Он нужен для выявления узких мест и оптимизации кода.

12. Что такое интегрированная среда разработки?  
  
    Интегрированная среда разработки (IDE) — это программа, которая объединяет множество инструментов для разработки программного обеспечения, включая редактор кода, компилятор, отладчик и интерфейс для управления проектами. 

Инсталляция программ  
Большинство современных программ требуется устанавливать (инсталлировать). Это связано с тем, что:  
- необходимо проверить, соответствует ли компьютер требованиям (к процессору, оперативной памяти, операционной системе и т. д.), которые обязательны для работы программы;  
- программы содержат множество файлов, которые должны быть корректно размещены в файловой системе для дальнейшей работы.

### параграф 42

1. Что такое инсталляция? Почему она необходима для многих современных программ?  
   Инсталляция — это процесс установки программного обеспечения на компьютер или устройство. Она необходима, чтобы настроить программу для работы в конкретной системе, обеспечить правильное расположение файлов и настроить интеграцию с операционной системой.

2. Что происходит во время инсталляции?  
   Во время инсталляции создаются необходимые каталоги, копируются файлы программы, устанавливаются системные библиотеки, настраиваются параметры конфигурации и могут производиться изменения в реестре (в Windows) или системных конфигурациях.

3. Что такое дистрибутив? В чём его отличие от установленной программы?  
   Дистрибутив — это пакет программного обеспечения, содержащий все необходимые файлы для установки программы. Он отличается от установленной программы тем, что дистрибутив ещё не содержит всех необходимых настроек и интеграций с операционной системой.

4. Что такое менеджер пакетов?  
   Менеджер пакетов — это инструмент, который автоматизирует установку, обновление и удаление программного обеспечения. Он управляет зависимостями и может устанавливать программы из централизованных репозиториев.

5. Как устанавливаются программы в разных операционных системах?  
   - Windows: Программы обычно устанавливаются с помощью дистрибутивов в формате .exe или .msi, с графическим интерфейсом, который проводит пользователя через шаги установки.  
   - Linux: Используются менеджеры пакетов (например, APT, YUM), которые могут устанавливать программы из репозиториев с помощью команд в терминале или графических интерфейсов (например, Synaptic).

6. Какие методы используются для массовой установки ПО?  
   Методы для массовой установки ПО включают использование скриптов автоматизации, образов систем (например, Ghost), групповых политик для Windows и специализированные инструменты управления в корпоративной среде.

7. Что такое переносимая программа?  
   Переносимая программа — это версия программного обеспечения, которая не требует установки и может быть запущена непосредственно с внешнего носителя, например, USB-накопителя. Это облегчает использование программы на разных устройствах.

8. Как можно познакомиться с операционной системой, не устанавливая её на жёсткий диск?  
   Для ознакомления с операционной системой можно использовать "живые диски" (Live-CD), которые позволяют загрузить систему с USB-накопителя или DVD без установки на жесткий диск.

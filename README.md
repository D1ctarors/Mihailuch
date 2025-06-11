<br clear="both">

<div align="center">
  <img height="350" width="100%" src="https://media.tenor.com/hVX6r4kDu00AAAAj/ai-grok.gif" />
</div>

###

<h1 align="center">👋 Всем здравствуйте!</h1>
<p align="center">Программист с трёхлетним стажем, люблю решать сложные задачи и создавать надёжные решения с нуля.</p>

###

<h2 align="left">Контакты</h2>

<div align="left">
  <a href="https://t.me/M1hailuch" target="_blank"><img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=2CA5E0" height="40" alt="telegram logo" /></a><img width="5" />
</div>

###
<h2 align="left">Профессиональный опыт</h2>

<div>
  <h3>1. Система мониторинга дронов с авторизацией и БД MySQL</h3>
  <div>
    <ul>
      <li>Цель проекта: предоставить веб-интерфейс для наблюдения за состоянием парка БПЛА с разграничением прав доступа операторов и администраторов.</li>
      <li>Технологии: HTML, CSS, Bootstrap 5, Sass, JavaScript, Django, MySQL.</li>
      <li>Роль и задачи:
        <ul>
          <li>Спроектировать структуру базы данных (пользователи, дроны, сессии мониторинга).</li>
          <li>Реализовать аутентификацию и роли на Django (регистрация, вход, восстановление пароля).</li>
          <li>Настроить REST-API для приёма телеметрии и сохранения в MySQL.</li>
          <li>Сверстать адаптивные дашборды на Bootstrap 5 + Sass: графики, таблицы, фильтры.</li>
          <li>Обеспечить автообновление данных через WebSocket или AJAX-пулл каждые 5–10 секунд.</li>
        </ul>
      </li>
      <li>Результат: надёжный и защищённый интерфейс, обрабатывающий тысячи запросов; документированное API с тестами.</li>
    </ul>
  </div>
</div>
<div>
  <h3>2. Система передачи телеметрии, видеопотока и управления дроном по Интернету</h3>
  <div>
    <ul>
      <li>Цель проекта: обеспечить удалённое управление БПЛА и просмотр видео в реальном времени через веб-интерфейс.</li>
      <li>Технологии: Python, pymavlink, requests.</li>
      <li>Роль и задачи:
        <ul>
          <li>Написать модуль для связи с автопилотом по MAVLink.</li>
          <li>Реализовать HTTP(S)-клиент на базе requests для обмена данными с сервером.</li>
          <li>Настроить MJPEG- или WebRTC-стриминг видео с борта дрона.</li>
          <li>Организовать очередь команд с подтверждениями и повторными отправками.</li>
        </ul>
      </li>
      <li>Результат: система с задержкой управления <200 мс и плавным видеопотоком для дистанционных тестов миссий.</li>
    </ul>
  </div>
</div>
<div>
  <h3>3. Модернизация прошивки ArduPilot</h3>
  <div>
    <ul>
      <li>Цель проекта: добавить поддержку нового типа MAVLink-сообщения и стороннего устройства.</li>
      <li>Технологии: C++, C#.</li>
      <li>Роль и задачи:
        <ul>
          <li>Изучить архитектуру ArduPilot и определить точки интеграции.</li>
          <li>Расширить XML-схему MAVLink, сгенерировать код и внедрить обработчики.</li>
          <li>Разработать драйвер для внешнего датчика: сбор данных, калибровка.</li>
          <li>Протестировать изменения в SITL и на реальном железе, написать модульные тесты.</li>
        </ul>
      </li>
      <li>Результат: официальная ветка прошивки с новым сенсором и командами, прошедшая полевые испытания.</li>
    </ul>
  </div>
</div>
<div>
  <h3>4. Модернизация Mission Planner</h3>
  <div>
    <ul>
      <li>Цель проекта: добавить поддержку нового MAVLink-сообщения и визуализировать данные устройства в GUI.</li>
      <li>Технологии: C#, WPF/WinForms.</li>
      <li>Роль и задачи:
        <ul>
          <li>Интеграция нового сообщения в десериализатор пакетов Mission Planner.</li>
          <li>Создание виджета с графиками и индикаторами состояния устройства.</li>
          <li>Обеспечение адаптивности интерфейса под разные DPI и разрешения.</li>
          <li>Проведение юзабилити-тестирования с операторами.</li>
        </ul>
      </li>
      <li>Результат: расширенный Mission Planner с официальной поддержкой новых сообщений и устройств.</li>
    </ul>
  </div>
</div>
<div>
  <h3>5. Модернизация конфигуратора INAV</h3>
  <div>
    <ul>
      <li>Цель проекта: локализовать приложение на русский язык и улучшить UI.</li>
      <li>Технологии: C++ (Qt) или C#, ресурсы локализации.</li>
      <li>Роль и задачи:
        <ul>
          <li>Собрать строки в .ts/.resx и перевести их.</li>
          <li>Добавить переключатель языка в настройках.</li>
          <li>Отрегулировать стили (шрифты, отступы, контраст) для читаемости.</li>
          <li>Обновить установщик с выбором локали.</li>
        </ul>
      </li>
      <li>Результат: UI на русском, расширивший аудиторию в РФ и СНГ.</li>
    </ul>
  </div>
</div>
<div>
  <h3>6. Трекер объектов на OpenCV + YOLO</h3>
  <div>
    <ul>
      <li>Цель проекта: обнаруживать и отслеживать объекты в видеопотоке.</li>
      <li>Технологии: Python, OpenCV, YOLO (Darknet/PyTorch).</li>
      <li>Роль и задачи:
        <ul>
          <li>Подготовить датасет и обучить YOLO-модель на целевых классах.</li>
          <li>Реализовать захват и предобработку кадров, детекцию объектов.</li>
          <li>Интегрировать алгоритм трекинга (DeepSORT/SORT) для сохранения ID объектов.</li>
          <li>Оптимизировать производительность с многопоточностью и GPU-ускорением.</li>
        </ul>
      </li>
      <li>Результат: стабильный трекинг >30 fps для 720p-видео, готовый к интеграции.</li>
    </ul>
  </div>
</div>
<div>
  <h3>7. Работа с симуляторами AirSim и Gazebo. Создание карт</h3>
  <div>
    <ul>
      <li>Цель проекта: создать реалистичные среды для тестирования ПО дронов.</li>
      <li>Технологии: Unreal Engine 4.27, AirSim, Gazebo, плагин AirSim Levels.</li>
      <li>Роль и задачи:
        <ul>
          <li>Интегрировать AirSim в UE 4.27 и собрать плагин для Gazebo.</li>
          <li>Проектировать ландшафты (город, лес, поле) с препятствиями и точками интереса.</li>
          <li>Генерировать heightmap, добавлять текстуры и физические коллайдеры.</li>
          <li>Создать скрипты для автоматического запуска миссий и сбора логов.</li>
        </ul>
      </li>
      <li>Результат: готовые карты для проверки планирования полёта, визуального позиционирования и SLAM.</li>
    </ul>
  </div>
</div>

###

<h2 align="left">Стек</h2>

<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a><img width="12" /><a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode.svg" width="36" height="36" alt="VS Code" /></a><img width="12" /><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a><img width="12" /><a href="https://sass-lang.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/sass-colored.svg" width="36" height="36" alt="Sass" /></a><img width="12" /><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a><img width="12" /><a href="https://getbootstrap.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/bootstrap-colored.svg" width="36" height="36" alt="Bootstrap" /></a><img width="12" /><a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" /></a><img width="12" /><a href="https://www.raspberrypi.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/raspberrypi-colored.svg" width="36" height="36" alt="Raspberry Pi" /></a>
</p>


###

<h2 align="left">Статистика</h2>

<div style="display: flex; align-items: center; gap: 1rem;">
  <img src="https://github-readme-stats.vercel.app/api?username=D1ctarors&show_icons=true" alt="Github stats" height="195px" />
  <img src="https://github.r2v.ch/codewars?user=D1ctarors&theme=light&top_languages=false" height="195" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=D1ctarors&layout=donut&theme=white&hide_border=true" alt="Top langs" height="195px" />
</div>





<style>
.u-carousel {
  --u-width: min(1200px, 96vw);
  --u-height: min(72vh, 720px);
  --u-radius: 18px;

  width: var(--u-width);
  margin: 24px auto;
  color: inherit;
  font-family: system-ui, sans-serif;
}

.u-carousel * {
  box-sizing: border-box;
}

.u-carousel__viewer {
  position: relative;
  width: 100%;
  height: var(--u-height);
  background: transparent;
  border-radius: var(--u-radius);
  overflow: hidden;
  border: 1px solid color-mix(in srgb, currentColor 14%, transparent);
  box-shadow: 0 12px 40px color-mix(in srgb, currentColor 12%, transparent);
}

.u-carousel__stage {
  position: relative;
  width: 100%;
  height: 100%;
  background: transparent;
}

.u-carousel__item {
  position: absolute;
  inset: 0;
  display: none;
  width: 100%;
  height: 100%;
  background: transparent;
}

.u-carousel__item.is-active {
  display: block;
}

.u-carousel__item img,
.u-carousel__item video {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center center;
  background: transparent;
}

.u-carousel__iframe-wrap {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.u-carousel__iframe-wrap iframe {
  display: block;
  width: 95%;
  height: 95%;
  border: none;
  background: transparent;
}

.u-carousel__arrow {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  z-index: 5;
  width: 54px;
  height: 54px;
  border: 1px solid color-mix(in srgb, currentColor 14%, transparent);
  border-radius: 999px;
  background: color-mix(in srgb, currentColor 10%, transparent);
  color: inherit;
  font-size: 28px;
  line-height: 1;
  cursor: pointer;
  backdrop-filter: blur(6px);
}

.u-carousel__arrow:hover {
  background: color-mix(in srgb, currentColor 16%, transparent);
}

.u-carousel__arrow--prev {
  left: 14px;
}

.u-carousel__arrow--next {
  right: 14px;
}

.u-carousel__caption {
  margin-top: 10px;
  padding: 10px 14px;
  border-radius: 12px;
  background: color-mix(in srgb, currentColor 8%, transparent);
  color: inherit;
  font-size: 14px;
  line-height: 1.45;
  border: 1px solid color-mix(in srgb, currentColor 14%, transparent);
}

.u-carousel__caption:empty {
  display: none;
}

.u-carousel__caption a {
  color: inherit;
  text-decoration-line: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 0.14em;
  text-decoration-skip-ink: auto;
}

.u-carousel__caption a:hover {
  opacity: 0.8;
}

.u-carousel__bottom {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-top: 12px;
}

.u-carousel__counter {
  flex: 0 0 auto;
  min-width: 84px;
  text-align: center;
  font-size: 14px;
  color: color-mix(in srgb, currentColor 72%, transparent);
}

.u-carousel__thumbs {
  display: flex;
  gap: 8px;
  overflow-x: auto;
  padding-bottom: 4px;
  flex: 1 1 auto;
}

.u-carousel__thumb {
  flex: 0 0 auto;
  min-width: 40px;
  height: 36px;
  padding: 0 12px;
  border: 1px solid color-mix(in srgb, currentColor 14%, transparent);
  border-radius: 999px;
  background: color-mix(in srgb, currentColor 8%, transparent);
  color: inherit;
  cursor: pointer;
}

.u-carousel__thumb:hover {
  background: color-mix(in srgb, currentColor 12%, transparent);
}

.u-carousel__thumb.is-active {
  background: color-mix(in srgb, currentColor 16%, transparent);
  border-color: currentColor;
  box-shadow: inset 0 0 0 1px currentColor;
  font-weight: 600;
}

@media (max-width: 700px) {
  .u-carousel {
    --u-height: 58vh;
  }

  .u-carousel__arrow {
    width: 46px;
    height: 46px;
    font-size: 24px;
  }

  .u-carousel__bottom {
    flex-direction: column;
    align-items: stretch;
  }

  .u-carousel__counter {
    min-width: auto;
  }

  .u-carousel__iframe-wrap iframe {
    width: 100%;
    height: 100%;
  }
}

.audio-player {
  display: flex;
  justify-content: center;
  margin: 1.5rem 0;
}

.audio-player audio {
  width: min(100%, 480px);
}
</style>

# Вверх вдоль Яузы к Ботаническому саду, ВДНХ, Останкино

## Если пройтись по маршруту:

### Дорога к Яузе

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_084823.jpg" alt="">
  <img src="img/PANO_20260501_085254.jpg" alt="" data-caption="Речка Будайка">
  <img src="img/PANO_20260501_085515.jpg" alt="" data-caption="Тут речку Будайку пришлось перейти вброд">
  <img src="img/PANO_20260501_090814.jpg" alt="">
</div>

### Долина Яузы

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_091808.jpg" alt="">
  <img src="img/PANO_20260501_092807.jpg" alt="">
  <video src="img/VID_20260501_092944.mp4" controls preload="metadata"></video>
</div>

#### [Парк Акведук](https://yandex.com/maps/-/CPWFeT9W)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_093226.jpg" alt="">
  <img src="img/PANO_20260501_093358.jpg" alt="">
  <img src="img/PANO_20260501_093711.jpg" alt="">
  <img src="img/IMG_20260501_093950.jpg" alt="" data-caption="К несчастью, проход на акведук был закрыт">
  <img src="img/IMG_20260501_094229.jpg" alt="" data-caption="Спойлер того, что ждёт дальше">
  <img src="img/PANO_20260501_094322.jpg" alt="">
  <img src="img/IMG_20260501_094425.jpg" alt="">
  <img src="img/IMG_20260501_094451.jpg" alt="">
  <img src="img/IMG_20260501_094610.jpg" alt="">
  <img src="img/IMG_20260501_094655.jpg" alt="">
  <img src="img/IMG_20260501_094900.jpg" alt="">
  <img src="img/IMG_20260501_095101.jpg" alt="">
  <img src="img/PANO_20260501_095443.jpg" alt="">
</div>

#### [Парк спорта Яуза](https://yandex.com/maps/-/CPWFe8KO)

<div class="u-carousel" data-u-carousel>
  <img src="img/IMG_20260501_095947.jpg" alt="">
  <img src="img/PANO_20260501_100143.jpg" alt="">
  <img src="img/PANO_20260501_100515.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWJbFp~">Безымянный островок</a>'>
  <img src="img/IMG_20260501_100805.jpg" alt="">
</div>

#### [Парк "Сад будущего"](https://yandex.com/maps/-/CPWFq2Na)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_101327.jpg" alt="">
  <img src="img/PANO_20260501_101558.jpg" alt="" data-caption="На противоположном берегу можете разглядеть гусей">
  <video src="img/VID_20260501_101808.mp4" controls preload="metadata"></video>
  <video src="img/VID_20260501_101937.mp4" controls preload="metadata"></video>
  <iframe
    src="https://drive.google.com/file/d/1KpI335ppO-Y3RQxHRzPbxO2_EfQsPllF/preview"
    allow="autoplay; fullscreen"
    allowfullscreen>
  </iframe>
  <video src="img/VID_20260501_102348.mp4" controls preload="metadata"></video>
  <video src="img/VID_20260501_104149.mp4" controls preload="metadata"></video>
  <img src="img/PANO_20260501_111548.jpg" alt="">
  <img src="img/PANO_20260501_111627.jpg" alt="">
  <img src="img/PANO_20260501_111837.jpg" alt="">
  <img src="img/PANO_20260501_112144.jpg" alt="">
  <img src="img/PANO_20260501_112531.jpg" alt="">
</div>

#### [Парк Хуамин](https://yandex.com/maps/-/CPWFyF4p)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_113353.jpg" alt="">
  <img src="img/PANO_20260501_114003.jpg" alt="">
  <img src="img/PANO_20260501_114324.jpg" alt="">
  <img src="img/PANO_20260501_114513.jpg" alt="">
  <img src="img/PANO_20260501_114631.jpg" alt="">
  <img src="img/PANO_20260501_114946.jpg" alt="">
  <img src="img/IMG_20260501_115041.jpg" alt="">
  <img src="img/PANO_20260501_115226.jpg" alt="">
  <img src="img/PANO_20260501_115401.jpg" alt="">
  <img src="img/PANO_20260501_115834.jpg" alt="">
  <img src="img/PANO_20260501_120343.jpg" alt="">
  <video src="img/VID_20260501_120435.mp4" controls preload="metadata"></video>
  <img src="img/PANO_20260501_120506.jpg" alt="">
  <img src="img/PANO_20260501_120644.jpg" alt="">
  <img src="img/PANO_20260501_120914.jpg" alt="">
  <img src="img/PANO_20260501_121019.jpg" alt="">
  <img src="img/PANO_20260501_121109.jpg" alt="">
  <img src="img/PANO_20260501_121203.jpg" alt="">
  <img src="img/PANO_20260501_121256.jpg" alt="">
  <img src="img/PANO_20260501_121455.jpg" alt="">
  <img src="img/PANO_20260501_121712.jpg" alt="">
  <img src="img/PANO_20260501_121812.jpg" alt="">
  <img src="img/PANO_20260501_122001.jpg" alt="">
</div>

### Путь к Ботаническому саду

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_124329.jpg" alt="">
  <img src="img/PANO_20260501_125031.jpg" alt="">
</div>

### [Ботанический сад](https://yandex.com/maps/-/CPWFyDix)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_130155.jpg" alt="" data-caption-html='Закрытая <a href="https://yandex.com/maps/-/CPWfF0pk">Экспозиция культурных растений</a>'>
  <img src="img/PANO_20260501_131026.jpg" alt="">
  <img src="img/PANO_20260501_131753.jpg" alt="">
  <img src="img/IMG_20260501_134048.jpg" alt="" data-caption="Вот такие деревья водятся тут">
  <video src="img/VID_20260501_134920.mp4" controls preload="metadata" data-caption="И вот такие кряклы ходят"></video>
  <img src="img/PANO_20260501_135912.jpg" alt="">
  <img src="img/PANO_20260501_140150.jpg" alt="">
  <img src="img/PANO_20260501_140348.jpg" alt="">
  <img src="img/PANO_20260501_141445.jpg" alt="">
  <img src="img/PANO_20260501_141505.jpg" alt="" data-caption-html='Закрытая <a href="https://yandex.com/maps/-/CPWfZ20P">Новая фондовая оранжерея</a>'>
  <img src="img/PANO_20260501_142835.jpg" alt="">
  <img src="img/PANO_20260501_142903.jpg" alt="">
  <img src="img/PANO_20260501_143454.jpg" alt="">
  <video src="img/VID_20260501_143705.mp4" controls preload="metadata" data-caption="Конная полиция, жандармы!"></video>
  <img src="img/PANO_20260501_143925.jpg" alt="" data-caption-html='Закрытый <a href="https://yandex.com/maps/-/CPWfJ43I">Розарий</a>'>
  <img src="img/PANO_20260501_144114.jpg" alt="">
  <img src="img/PANO_20260501_144454.jpg" alt="">
  <img src="img/PANO_20260501_144540.jpg" alt="">
  <img src="img/PANO_20260501_152243.jpg" alt="">
  <img src="img/PANO_20260501_152721.jpg" alt="">
  <video src="img/VID_20260501_152752.mp4" controls preload="metadata"></video>
  <img src="img/PANO_20260501_155248.jpg" alt="">
  <img src="img/PANO_20260501_155325.jpg" alt="">
  <img src="img/PANO_20260501_160213.jpg" alt="" data-caption="Очередной спойлер">
  <img src="img/PANO_20260501_160303.jpg" alt="">
</div>

#### [Японский сад](https://yandex.com/maps/-/CPWJnDO-)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_130353.jpg" alt="">
  <img src="img/PANO_20260501_130641.jpg" alt="">
  <img src="img/PANO_20260501_131229.jpg" alt="">
  <img src="img/IMG_20260501_133043.jpg" alt="">
  <img src="img/PANO_20260501_133217.jpg" alt="">
  <img src="img/PANO_20260501_133237.jpg" alt="">
  <img src="img/PANO_20260501_133330.jpg" alt="">
  <img src="img/IMG_20260501_133405.jpg" alt="">
  <img src="img/PANO_20260501_133425.jpg" alt="">
  <img src="img/IMG_20260501_133515.jpg" alt="">
  <img src="img/PANO_20260501_133538.jpg" alt="">
  <video src="img/VID_20260501_133626.mp4" controls preload="metadata"></video>
</div>

### [ВДНХ](https://yandex.com/maps/-/CPWF565O)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_153459.jpg" alt="">
  <img src="img/PANO_20260501_153735.jpg" alt="">
  <img src="img/PANO_20260501_154231.jpg" alt="">
  <video src="img/VID_20260501_160832.mp4" controls preload="metadata"></video>
  <img src="img/PANO_20260501_161338.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWfrM74">Лабиринт</a>'>
  <img src="img/PANO_20260501_163647.jpg" alt="">
  <img src="img/IMG_20260501_163732.jpg" alt="">
  <img src="img/PANO_20260501_164058.jpg" alt="">
  <img src="img/PANO_20260501_164625.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWf7IoX">Музей космонавтики</a>'>
  <img src="img/PANO_20260501_165607.jpg" alt="">
  <img src="img/PANO_20260501_165912.jpg" alt="">
  <img src="img/PANO_20260501_170142.jpg" alt="">
  <img src="img/PANO_20260501_170321.jpg" alt="">
  <img src="img/PANO_20260501_170539.jpg" alt="">
  <img src="img/PANO_20260501_170852.jpg" alt="">
  <img src="img/PANO_20260501_171520.jpg" alt="">
  <img src="img/IMG_20260501_171916.jpg" alt="" data-caption="Снова спойлер">
  <img src="img/PANO_20260501_175845.jpg" alt="">
</div>

### [Рабочий и колхозница](https://yandex.com/maps/-/CPWFBJzC)

<figure>
  <center>
    <img src="img/IMG_20260501_172806.jpg"/>
  </center>
</figure>

### [Космопарк](https://yandex.com/maps/-/CPWFB-nI)

<div class="u-carousel" data-u-carousel>
  <img src="img/IMG_20260501_180306.jpg" alt="">
  <img src="img/IMG_20260501_180508.jpg" alt="">
  <img src="img/IMG_20260501_180815.jpg" alt="">
  <img src="img/PANO_20260501_181042.jpg" alt="">
  <img src="img/PANO_20260501_180711.jpg" alt="">
  <img src="img/IMG_20260501_181340.jpg" alt="">
  <img src="img/IMG_20260501_181447.jpg" alt="">
  <img src="img/PANO_20260501_181601.jpg" alt="">
</div>

### [Останкинский парк](https://yandex.com/maps/-/CPWFFNNG)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_183524.jpg" alt="">
  <img src="img/PANO_20260501_183813.jpg" alt="">
  <img src="img/PANO_20260501_184347.jpg" alt="">
  <img src="img/IMG_20260501_205028.jpg" alt="" data-caption="Те же деревья, но уже потом, когда Солнце село">
  <img src="img/IMG_20260501_185117.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWjQ23N">Белочка</a>'>
  <img src="img/PANO_20260501_192051.jpg" alt="">
</div>

### Возвращение на ВДНХ

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_194223.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWjIZMQ">Зелёный лабиринт</a> снаружи'>
  <img src="img/PANO_20260501_194318.jpg" alt="" data-caption-html='<a href="https://yandex.com/maps/-/CPWjIZMQ">Зелёный лабиринт</a> внутри'>
  <img src="img/IMG_20260501_194443.jpg" alt="">
  <img src="img/IMG_20260501_195942.jpg" alt="">
  <img src="img/IMG_20260501_200041.jpg" alt="">
  <img src="img/PANO_20260501_200454.jpg" alt="">
  <img src="img/PANO_20260501_200600.jpg" alt="">
  <img src="img/PANO_20260501_201158.jpg" alt="">
</div>

#### [Воздушная экотропа](https://yandex.com/maps/-/CPWfzE3i)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_192936.jpg" alt="">
  <img src="img/PANO_20260501_193321.jpg" alt="">
  <img src="img/PANO_20260501_193531.jpg" alt="">
</div>

#### [Лента Мёбиуса](https://yandex.com/maps/-/CPWfzMkn)

<div class="u-carousel" data-u-carousel>
  <img src="img/PANO_20260501_195744.jpg" alt="">
  <img src="img/PANO_20260501_194843.jpg" alt="">
  <img src="img/IMG_20260501_195239.jpg" alt="" data-caption="Спойлер, последний раз (что ж сделать, если эту башню отовсюду видно)">
  <img src="img/PANO_20260501_195243.jpg" alt="">
  <img src="img/PANO_20260501_195356.jpg" alt="">
  <img src="img/IMG_20260501_195446.jpg" alt="">
</div>

### [Останкинская башня](https://yandex.com/maps/-/CPWFFTjP)

<div class="u-carousel" data-u-carousel>
  <img src="img/IMG_20260501_183110.jpg" alt="" data-caption="Останкинская башня пока ещё Солнце не село">
  <img src="img/IMG_20260501_210151.jpg" alt="">
  <img src="img/IMG_20260501_210840.jpg" alt="">
  <img src="img/PANO_20260501_210851.jpg" alt="">
  <img src="img/IMG_20260501_210952.jpg" alt="">
  <img src="img/IMG_20260501_212201.jpg" alt="" data-caption="Останкинская башня почти вплотную">
  <img src="img/PANO_20260501_212839.jpg" alt="">
</div>

### [Галерея звёзд](https://yandex.com/maps/-/CPWjMPzx)

<div class="u-carousel" data-u-carousel>
  <img src="img/IMG_20260501_211102.jpg" alt="">
  <img src="img/IMG_20260501_211154.jpg" alt="">
  <img src="img/IMG_20260501_211437.jpg" alt="" data-caption="Вот уж кого-кого, а Капицу (пусть и сына) увидеть я тут точно не ожидал">
  <img src="img/IMG_20260501_211457.jpg" alt="">
  <img src="img/IMG_20260501_211539.jpg" alt="">
  <img src="img/IMG_20260501_212124.jpg" alt="">
  <iframe
    src="https://drive.google.com/file/d/1OTlU3w9fMLdul_-n8fkk9pYFAu0emxa_/preview"
    allow="autoplay; fullscreen"
    allowfullscreen
    data-caption="А ещё там может в какой-то момент запуститься вот такое шоу, запустилось когда я был напротив Петросяна">
  </iframe>
</div>

<!-- Вставить маршрут -->

## Послесловие

<script>
(function () {
  function isMedia(node) {
    return node instanceof HTMLElement &&
      (
        node.tagName === 'IMG' ||
        node.tagName === 'VIDEO' ||
        node.tagName === 'IFRAME'
      );
  }

  function stopOtherVideos(mediaNodes, activeIndex) {
    mediaNodes.forEach(function (node, i) {
      if (node.tagName === 'VIDEO' && i !== activeIndex) {
        node.pause();
      }
    });
  }

  function syncIframes(mediaNodes, activeIndex) {
    mediaNodes.forEach(function (node, i) {
      if (node.tagName !== 'IFRAME') return;

      var originalSrc = node.dataset.uOriginalSrc || '';

      if (!originalSrc && node.getAttribute('src')) {
        originalSrc = node.getAttribute('src');
        node.dataset.uOriginalSrc = originalSrc;
      }

      if (i === activeIndex) {
        if (originalSrc && node.getAttribute('src') !== originalSrc) {
          node.setAttribute('src', originalSrc);
        }
      } else {
        if (node.getAttribute('src')) {
          node.setAttribute('src', '');
        }
      }
    });
  }

  function buildCarousel(root) {
    if (root.dataset.uCarouselReady === 'true') return;

    var sourceNodes = Array.from(root.children).filter(isMedia);
    if (!sourceNodes.length) return;

    var mediaNodes = sourceNodes;

    mediaNodes.forEach(function (node) {
      if (node.tagName === 'VIDEO') {
        if (!node.hasAttribute('preload')) {
          node.setAttribute('preload', 'metadata');
        }
        node.setAttribute('playsinline', '');
        node.setAttribute('webkit-playsinline', '');
      }

      if (node.tagName === 'IMG' && !node.hasAttribute('alt')) {
        node.setAttribute('alt', '');
      }

      if (node.tagName === 'IFRAME') {
        if (!node.hasAttribute('loading')) {
          node.setAttribute('loading', 'lazy');
        }
        if (!node.hasAttribute('allowfullscreen')) {
          node.setAttribute('allowfullscreen', '');
        }
        if (!node.hasAttribute('referrerpolicy')) {
          node.setAttribute('referrerpolicy', 'strict-origin-when-cross-origin');
        }
        if (!node.hasAttribute('allow')) {
          node.setAttribute('allow', 'autoplay; fullscreen');
        }

        if (node.getAttribute('src')) {
          node.dataset.uOriginalSrc = node.getAttribute('src');
        }
      }
    });

    root.replaceChildren();

    var viewer = document.createElement('div');
    viewer.className = 'u-carousel__viewer';

    var stage = document.createElement('div');
    stage.className = 'u-carousel__stage';

    var prev = document.createElement('button');
    prev.type = 'button';
    prev.className = 'u-carousel__arrow u-carousel__arrow--prev';
    prev.setAttribute('aria-label', 'Previous slide');
    prev.textContent = '‹';

    var next = document.createElement('button');
    next.type = 'button';
    next.className = 'u-carousel__arrow u-carousel__arrow--next';
    next.setAttribute('aria-label', 'Next slide');
    next.textContent = '›';

    var caption = document.createElement('div');
    caption.className = 'u-carousel__caption';

    var bottom = document.createElement('div');
    bottom.className = 'u-carousel__bottom';

    var counter = document.createElement('div');
    counter.className = 'u-carousel__counter';

    var thumbs = document.createElement('div');
    thumbs.className = 'u-carousel__thumbs';

    var items = mediaNodes.map(function (node, i) {
      var item = document.createElement('div');
      item.className = 'u-carousel__item';

      if (node.tagName === 'IFRAME') {
        var wrap = document.createElement('div');
        wrap.className = 'u-carousel__iframe-wrap';
        wrap.appendChild(node);
        item.appendChild(wrap);
      } else {
        item.appendChild(node);
      }

      stage.appendChild(item);

      if (node.tagName === 'VIDEO') {
        node.load();
      }

      var thumb = document.createElement('button');
      thumb.type = 'button';
      thumb.className = 'u-carousel__thumb';

      if (node.tagName === 'VIDEO') {
        thumb.textContent = '▶ ' + (i + 1);
      } else if (node.tagName === 'IFRAME') {
        thumb.textContent = '▣ ' + (i + 1);
      } else {
        thumb.textContent = String(i + 1);
      }

      thumbs.appendChild(thumb);

      return {
        wrap: item,
        media: node,
        thumb: thumb,
        caption: node.dataset.caption || '',
        captionHtml: node.dataset.captionHtml || ''
      };
    });

    viewer.appendChild(prev);
    viewer.appendChild(stage);
    viewer.appendChild(next);

    bottom.appendChild(counter);
    bottom.appendChild(thumbs);

    root.appendChild(viewer);
    root.appendChild(caption);
    root.appendChild(bottom);

    var index = 0;

    function update() {
      items.forEach(function (item, i) {
        var active = i === index;
        item.wrap.classList.toggle('is-active', active);
        item.thumb.classList.toggle('is-active', active);
      });

      var allMedia = items.map(function (item) { return item.media; });

      stopOtherVideos(allMedia, index);
      syncIframes(allMedia, index);

      counter.textContent = (index + 1) + ' / ' + items.length;

      if (items[index].captionHtml) {
        caption.innerHTML = items[index].captionHtml;
      } else {
        caption.textContent = items[index].caption || '';
      }
    }

    items.forEach(function (item, i) {
      item.thumb.addEventListener('click', function () {
        index = i;
        update();
      });
    });

    prev.addEventListener('click', function () {
      index = (index - 1 + items.length) % items.length;
      update();
    });

    next.addEventListener('click', function () {
      index = (index + 1) % items.length;
      update();
    });

    root.tabIndex = 0;
    root.addEventListener('keydown', function (e) {
      if (e.key === 'ArrowLeft') {
        e.preventDefault();
        index = (index - 1 + items.length) % items.length;
        update();
      }

      if (e.key === 'ArrowRight') {
        e.preventDefault();
        index = (index + 1) % items.length;
        update();
      }
    });

    root.dataset.uCarouselReady = 'true';
    update();
  }

  function initAll() {
    document.querySelectorAll('[data-u-carousel]').forEach(buildCarousel);
  }

  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', initAll);
  } else {
    initAll();
  }
})();
</script>

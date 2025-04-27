# Landing-Britlex-ForeignLanguage
My educational pet project is a landing page for a non-existent English language school Britlex. 

RU

Мой учебный pet-проект – лендинг несуществующей школы английского языка Britlex. Монохромный дизайн в стиле минимализм. Ссылка на макет https://pixso.net/app/editor/saZWKfFxGp68a60JngvdbQ

Надо сказать, что макет во многом некачественно сделан. Во-первых, иерархии и группировки в слоях нет совсем – все слои хаотично разбросаны по панели слоёв. Поэтому я сам сгруппировал слои – но только для фрейма Landing (1600), ибо нужно же было от чего-то "плясать".

Далее, многие дочерние фреймы очень неаккуратно сделаны – их размер намного больше содержимого, они наезжают друг на другу и т.п. Например, пункты меню хэдера дизайнер прописал одной строкой текста – поэтому понять какие между ними отступы невозможно. А ещё разные отступы между секциями, разные gap, разные размеры шрифта заголовков и абзацев и т.д.

Отсюда следует, что делать pixel-perfect нет смысла – поэтому при работе руководствовался только здравым смыслом.

Размер шрифта абзацев секции Skills в макете = 16px, когда в других секциях у абзацев размер шрифта = 20px. Поэтому выставил тоже 20, а line height: normal.

Также, в заголовках H1 / H2 используется абсолютно черный цвет #000 ! Поэтому я использовал #333 .

Что было сделано ещё?

Поменял местами второй и третий блоки цифр-статистик about__statistic-item – в первоначальном варианте визуально казалось, что родитель about__statistic выровнен по левому краю экрана.

Картинки svg для секций Skills и Pricing я выровнял (в макете) по высоте, с сохранением пропорций.

Некоторые экспортированные svg картинки, перед внедрением их в вёрстку, сжал в сервисе SVGOMG https://jakearchibald.github.io/svgomg/ – сжатие получается примерно в 2 раза.

Так как на мобильных экранах меню выводится в виде бургера, то на него было "повешено" меню из фреймворка Materialize.

В вёрстке активно применял модули grid и flex, CSS переменные (для цветов), относительные единицы измерения % и vw, а классы старался писать по методологии БЭМ.


ENG

My educational pet project is a landing page for a non-existent English language school Britlex. Monochrome design in a minimalist style. Link to the layout https://pixso.net/app/editor/saZWKfFxGp68a60JngvdbQ

I must say that the layout is poorly done in many ways. Firstly, there is no hierarchy or grouping in the layers at all - all the layers are scattered chaotically across the layers panel. Therefore, I grouped the layers myself - but only for the Landing frame (1600), because I had to "dance" from something.

Further, many child frames are very sloppily done - their size is much larger than the content, they overlap each other, etc. For example, the designer wrote the header menu items in one line of text - so it is impossible to understand what the indents are between them. And also different indents between sections, different gaps, different font sizes of headings and paragraphs, etc.

It follows that there is no point in making pixel-perfect - so I was guided only by common sense when working.

The font size of paragraphs in the Skills section in the layout = 16px, when in other sections the paragraphs have a font size of 20px. Therefore, I also set it to 20, and line height: normal.

Also, the H1 / H2 headings use the absolute black color #000 ! Therefore, I used #333 .

What else was done?

I swapped the second and third blocks of statistics figures about__statistic-item - in the original version it visually seemed that the parent about__statistic was aligned to the left edge of the screen.

I aligned the svg images for the Skills and Pricing sections (in the layout) by height, while maintaining the proportions.

Some exported svg images were compressed in the SVGOMG service https://jakearchibald.github.io/svgomg/ before being implemented into the layout – the compression is approximately 2 times.

Since the menu is displayed as a burger on mobile screens, the menu from the Materialize framework was "hung" on it.

In the layout, I actively used the grid and flex modules, CSS variables (for colors), relative units of measurement % and vw, and I tried to write classes using the BEM methodology.

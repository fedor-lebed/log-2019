# log-2019

> сверху - новое

### 25.11.2019

Введем мн-во выч. графов __G(n, m)__ с __n__ входами и __m__ выходами и некоторую ф-ию сложности схемы __S: G(n, m) -> R__.
Будем рассматривать __S__ как <img src="https://render.githubusercontent.com/render/math?math=-\alpha\log p(G)"> - априорное распеределение на __G(n, m)__.

Тогда <img src="https://render.githubusercontent.com/render/math?math=p(t|xTX) = E_{G~G|XT}p(t|xG)">.
Для оценки G~G|XT будем использовать MCMC, с предложенным распределением, основанным на некоторой процедуре жадной оптимизации.

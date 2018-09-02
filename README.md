# get_roi
Задача: посчитать ROI в разрезе типов источников трафика. Т. е. получить значения ROI по типам.
Типы определяются следующим образом:
* если source равен 'google' или 'yandex', то проверяем medium:
* для medium 'seo' или 'sem' тип источника равен 'search engines seo'
* для medium 'brand' - тип источника равен 'search engines brand'
* для остальных случаев тип источника равен 'search engines undefined'
* если условие не выполнено, то тип источника равен 'other'

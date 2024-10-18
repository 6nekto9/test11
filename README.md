1. Если нужны четкие, адаптивные или анимированные элементы интерфейса,иконки, логотипы, векторные изображения, то лучше всего использовать формат SVG.
2. Посмотреть x и y
3. <!DOCTYPE html>
<html>
<head>
<title>HTML, CSS and JavaScript demo</title>
</head>
 <link rel="stylesheet" href="style.css">
<body>
<svg width="200px" height="200px" viewBox="0 0 200 200">
<circle cx="30" cy="30" r="20" style="stroke: black; fill: none;" />
<circle cx="80" cy="30" r="20" style="stroke-width: 5; stroke: black; fill:
none;" />
<ellipse cx="30" cy="80" rx="10" ry="20" style="stroke: black; fill: red ;" />
<ellipse cx="80" cy="80" rx="20" ry="10" style="stroke: black; fill: yellow;" />

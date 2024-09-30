...html
     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typography Showcase</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Typography Showcase</h1>
    <section>
        <h2>Font Families</h2>
        <p class="serif">This is a serif font.</p>
        <p class="sans-serif">This is a sans-serif font.</p>
        <p class="monospace">This is a monospace font.</p>
    </section>
    <section>
        <h2>Font Sizes</h2>
        <p class="small">This is small text.</p>
        <p class="medium">This is medium text.</p>
        <p class="large">This is large text.</p>
    </section>
    <section>
        <h2>Font Weights</h2>
        <p class="light">This is light text.</p>
        <p class="normal">This is normal text.</p>
        <p class="bold">This is bold text.</p>
    </section>
    <section>
        <h2>Font Styles</h2>
        <p class="italic">This is italic text.</p>
        <p class="oblique">This is oblique text.</p>
    </section>
    <section>
        <h2>Line Heights</h2>
        <p class="tight">This is text with tight line height.</p>
        <p class="normal-line-height">This is text with normal line height.</p>
        <p class="loose">This is text with loose line height.</p>
    </section>
    <section>
        <h2>Text Transform</h2>
        <p class="uppercase">This is uppercase text.</p>
        <p class="lowercase">This is lowercase text.</p>
        <p class="capitalize">This is capitalized text.</p>
    </section>
</body>
</html>

...css
    body {
    font-family: Arial, sans-serif;
    margin: 20px;
    line-height: 1.6;
}

h1, h2 {
    color: #333;
}

section {
    margin-bottom: 20px;
}

.serif {
    font-family: 'Times New Roman', serif;
}

.sans-serif {
    font-family: Arial, sans-serif;
}

.monospace {
    font-family: 'Courier New', monospace;
}

.small {
    font-size: 12px;
}

.medium {
    font-size: 16px;
}

.large {
    font-size: 24px;
}

.light {
    font-weight: 300;
}

.normal {
    font-weight: 400;
}

.bold {
    font-weight: 700;
}

.italic {
    font-style: italic;
}

.oblique {
    font-style: oblique;
}

.tight {
    line-height: 1.2;
}

.normal-line-height {
    line-height: 1.6;
}

.loose {
    line-height: 2;
}

.uppercase {
    text-transform: uppercase;
}

.lowercase {
    text-transform: lowercase;
}

.capitalize {
    text-transform: capitalize;
}



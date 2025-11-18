[Uploadi<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Country Select</title>

<style>
    body {
        margin: 0;
        padding: 0;
        height: 100vh;
        width: 100vw;
        display: flex;
        overflow: hidden;
        font-family: "Georgia", serif;
    }

    /* Left and right panels */
    .side {
        width: 50%;
        height: 100%;
        position: relative;
        cursor: pointer;
        transition: filter 0.3s ease, transform 0.3s ease;
    }

    /* Germany background */
    .left {
        background-image: url("file:///C:/Users/daria/OneDrive/Dokumente/Website%20Game%20KoreaGermany/GermanyStartWebsite.jpg.jpg");
        background-size: cover;
        background-position: center;
    }

    /* Korea background */
    .right {
        background-image: url("file:///C:/Users/daria/OneDrive/Dokumente/Website%20Game%20KoreaGermany/JapanStartWebsite.jpg.jpg");
        background-size: cover;
        background-position: center;
    }

    /* Dark overlay on hover */
    .side:hover {
        filter: brightness(70%);
        transform: scale(1.02);
    }

    /* Center label text */
    .label {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background: rgba(0, 0, 0, 0.55);
        padding: 18px 40px;
        color: #fff;
        font-size: 28px;
        border-radius: 12px;
        letter-spacing: 1px;
    }

    /* Remove underline from click */
    a {
        text-decoration: none;
        color: inherit;
    }
</style>
</head>

<body>

<!-- Left side: Germany -->
<a href="GermanySecondPage.html" class="side left">
    <div class="label">Germany</div>
</a>

<!-- Right side: Korea -->
<a href="KoreaSecondPage.html" class="side right">
    <div class="label">Korea</div>
</a>

</body>
</html>
ng index.html.html…]()




<link rel="stylesheet" href="{{ url_for('static', filename='styles.css') }}">
<link rel="preconnect" href="https://fonts.googleapis.com">


<nav class="navbar-small">
        <ul>
            <li><a href="tel:+44762817811">Tel: 07762817811</a></li>
            <li><a href="mailto:rolsatech@gmail.com">rolsatech@gmail.com</a></li>
        </ul>
    </nav>

    <nav class="navbar">
    <img class="Logo" src="{{ url_for('static', filename='Images/Logo.png') }}">

    <ul>
        <li><a href="{{ url_for('index') }}">Home</a></li>
        <li><a href="{{ url_for('about') }}">About</a></li>
        <li><a href="{{ url_for('product_view') }}">Product View</a></li>
        <li><a href="{{ url_for('carbon') }}">Calculator</a></li>

    </ul>
    <div class="AccountNav">
        <a href="{{ url_for('login') }}">
            <i class="fa-solid fa-user"></i> Account
        </a>
</nav>

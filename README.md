<!DOCTYPE html>
<html lang="fr"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Salon Stream</title>
  <link rel="stylesheet" href="salonstream.css">
</head>
<body>
  <header>
    <nav>
      <div class="search-profile">
        <input type="text" class="search-bar" placeholder="Rechercher...">
        <button class="profile-btn">Identification</button>
        <h1>Salon Stream</h1>

        <div class="question-block">
          <label class="question-label" for="language">Langues</label>
          <select id="language">
            <option value="fr">Français</option>
            <option value="en">Anglais</option>
            <option value="jp">Japonais</option>
            <option value="ru">Russe</option>
            <option value="arb">Arabe</option>
          </select>
        </div>
      </div>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Découvrez le monde du cinéma et des séries tel que vous les aimez.</h1>
      <p>Des milliers de films et de séries en streaming illimité, à regarder dans votre salon, sur tablette ou smartphone.</p>
      <div class="cta-buttons">
        <button class="btn btn-primary">Commencer gratuitement dans votre salon, selon vos envies du moment.</button>
        <button class="btn btn-secondary">Continuer avec un abonnement premium pour voyager au-delà de votre salon.</button>
      </div>
    </div>
  </section>

  <section class="content-section">
    <h2 class="section-title">Déjà disponible sur notre plateforme</h2>
    <div class="video-grid">
      <div class="video-card">
        <div class="video-thumbnail"></div>
        <div class="video-info">
          <h3 class="video-title">Le chant des merguez</h3>
          <div class="video-meta">
            <span class="video-rating">★ 4.8</span>
            <span>2h 15min</span>
            <span>2024</span>
          </div>
        </div>
      </div>

      <div class="video-card">
        <div class="video-thumbnail"></div>
        <div class="video-info">
          <h3 class="video-title">À la recherche de la merguez qui chante</h3>
          <div class="video-meta">
            <span class="video-rating">★ 4.5</span>
            <span>1h 50min</span>
            <span>2024</span>
          </div>
        </div>
      </div>

      <div class="video-card">
        <div class="video-thumbnail"></div>
        <div class="video-info">
          <h3 class="video-title">Merguez contre chipolata sur une plancha grillée <br> (partie 1 ) </h3>
          <div class="video-meta">
            <span class="video-rating">★ 4.7</span>
            <span>35min</span>
            <span>2025</span>
          </div>
        </div>
      </div>
    </div>

    <h2 class="section-title">Notre sélection du moment</h2>
    <div class="video-grid">
      <div class="video-card">
        <div class="video-thumbnail"></div>
        <div class="video-info">
          <h3 class="video-title">Le voyage de la merguez qui pique<br> Documentaire</h3>
          <div class="video-meta">
            <span class="video-rating">★ 4.6</span>
            <span>1h 45min</span>
            <span>2023</span>
          </div>
        </div>
      </div>

      <div class="video-card">
        <div class="video-thumbnail"></div>
        <div class="video-info">
          <h3 class="video-title">La merguez qui sort de la barquette <br> Documentaire</h3>
          <div class="video-meta">
            <span class="video-rating">★ 4.7</span>
            <span>2h 10min</span>
            <span>2023</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-links">
      <a href="#">À propos</a>
      <a href="#">Centre d'aide</a>
      <a href="#">Conditions d'utilisation</a>
      <a href="#">Confidentialité</a>
      <a href="#">Nous contacter</a>
    </div>
    <div class="social-icons">
      <div class="social-icon">f</div>
      <div class="social-icon">t</div>
      <div class="social-icon">i</div>
      <div class="social-icon">y</div>
    </div>
    <p style="margin-top: 2rem; color: #666">© 2025 Salon Stream. Tous droits réservés.</p>
  </footer>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>

</body></html>

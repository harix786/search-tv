<h2>search-tv</h2>
<div>
  This application provides a safer way to search for TV torrents. There are no ads, no malicious code, and all requests are made to a <a href="https://glitch.me" target="_blank">glitch.me</a> server which does all the dirty work and returns a clean JSON object. The results returned are magnet links. You can click the link and it will open your torrent client or you can copy the link and add it to your client manually. A clone of this project is maintained at https://search-tv.glitch.me, if you want to use the app in your browser.
</div>
<br>
<div>
  If you want get the JSON search results without visiting the site, you can use the API on my glitch.me server. All you have to do is send a <code>GET</code> request to <code>https://search-tv.glitch.me/your%20url%20encoded%20search%20terms</code> and parse the returned JSON however you'd like.
</div>
<div>
  <h4>Request</h4>
  <code>https://search-tv.glitch.me/test%20me</code>
</div>
<div>
  <h4>Response</h4>
  <code>
    [ {"title":["Private Eyes S02E01 720p HDTV x264-KILLERS [eztv] (1.11 GB) Magnet Link"],"href":"magnet:?xt=urn:btih:5f66f5fd784d6ff92d2adb36bb7fc5a7d7d62f45&dn=Private.Eyes.S02E01.720p.HDTV.x264-KILLERS%5Beztv%5D.mkv%5Beztv%5D&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A80&tr=udp%3A%2F%2Fglotorrents.pw%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fexodus.desync.com%3A6969"}, ... ]
  </code>
</div>
<br>
<div>
  Built on GitHub's <a href='electron.atom.io' target='_blank'>Electron</a> framework.
</div>

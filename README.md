<h1 align="center">Hi 👋, I'm Emiliano Torres</h1>
<h3 align="center">A passionate full stack web developer from Argentina</h3>
<img align="right" src="https://media.giphy.com/media/bGgsc5mWoryfgKBx1u/giphy.gif" alt="gif" width="200"/>

- 📫 How to reach me **emiliano.dev.torres@gmail.com**


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="50" height="50"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="50" height="50"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="50" height="50"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="50" height="50"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="50" height="50"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="50" height="50"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="50" height="50"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="50" height="50"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="50" height="50"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="50" height="50"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="50" height="50"/> </a> </p>
<br/>
<br/>
<p>&nbsp;<img align="left" src="https://github-readme-stats.vercel.app/api?username=emilix22&show_icons=true&locale=en" alt="emilix22" /></p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=emilix22&show_icons=true&locale=en&layout=compact" alt="emilix22" /></p>

<!--header-->
<table>
  <tr><td colspan="2"><a href="/README.md#-plugins">← Back to plugins index</a></td></tr>
  <tr><th colspan="2"><h3>📅 Isometric commit calendar</h3></th></tr>
  <tr><td colspan="2" align="center"><p>This plugin displays an isometric view of a user commit calendar along with a few additional statistics like current streak and average number of commit per day.</p>
</td></tr>
  <tr><th>⚠️ Disclaimer</th><td><p>This plugin is not affiliated, associated, authorized, endorsed by, or in any way officially connected with <a href="https://github.com">GitHub</a>.
All product and company names are trademarks™ or registered® trademarks of their respective holders.</p>
</td></tr>
  <tr>
    <th rowspan="3">Supported features<br><sub><a href="metadata.yml">→ Full specification</a></sub></th>
    <td><a href="/source/templates/classic/README.md"><code>📗 Classic template</code></a> <a href="/source/templates/terminal/README.md"><code>📙 Terminal template</code></a></td>
  </tr>
  <tr>
    <td><code>👤 Users</code></td>
  </tr>
  <tr>
    <td><code>🔑 (scopeless)</code> <code>read:org (optional)</code> <code>read:user (optional)</code> <code>read:packages (optional)</code> <code>repo (optional)</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <details open><summary>Full year calendar</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg" alt=""></img></details>
      <details><summary>Half year calendar</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg" alt=""></img></details>
      <img width="900" height="1" alt="">
    </td>
  </tr>
</table>
<!--/header-->

## ➡️ Available options

<!--options-->
<table>
  <tr>
    <td align="center" nowrap="nowrap">Option</i></td><td align="center" nowrap="nowrap">Description</td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_isocalendar</code></h4></td>
    <td rowspan="2"><p>Enable isocalendar plugin</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>boolean</code>
<br>
<b>default:</b> no<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_isocalendar_duration</code></h4></td>
    <td rowspan="2"><p>Time range</p>
<ul>
<li><code>half-year</code>: 180 days</li>
<li><code>full-year</code>: 1 year</li>
</ul>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>string</code>
<br>
<b>default:</b> half-year<br>
<b>allowed values:</b><ul><li>half-year</li><li>full-year</li></ul></td>
  </tr>
</table>
<!--/options-->

## ℹ️ Examples workflows

<!--examples-->
```yaml
name: Half-year calendar
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.isocalendar.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_isocalendar: yes

```
```yaml
name: Full-year calendar
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.isocalendar.fullyear.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_isocalendar: yes
  plugin_isocalendar_duration: full-year

```
<!--/examples-->



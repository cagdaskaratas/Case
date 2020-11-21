<template>
  <div class="main-base">
    <section class="live-area">
      <b-col cols="12" class="main">
        <b-col cols="6" class="main-live">
          <button>LIVE</button>
          <p>Popular Matches</p>
        </b-col>
        <b-col cols="6" class="main-arrow">
          <b-col cols="12" class="arrow">
            <svg width="3em" height="2em" viewBox="0 0 16 16" class="bi bi-caret-left-fill"
                 style="color:#556385;position:relative;left: 25px;" fill="currentColor"
                 xmlns="http://www.w3.org/2000/svg">
              <path
                  d="M3.86 8.753l5.482 4.796c.646.566 1.658.106 1.658-.753V3.204a1 1 0 0 0-1.659-.753l-5.48 4.796a1 1 0 0 0 0 1.506z"/>
            </svg>
            <svg width="3em" height="2em" viewBox="0 0 16 16" class="bi bi-caret-right-fill"
                 style="color:#556385;position:relative;" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path
                  d="M12.14 8.753l-5.482 4.796c-.646.566-1.658.106-1.658-.753V3.204a1 1 0 0 1 1.659-.753l5.48 4.796a1 1 0 0 1 0 1.506z"/>
            </svg>
          </b-col>
        </b-col>
      </b-col>
      <b-col cols="12" class="card-base">
        <b-col cols="6" class="cards">
          <b-col cols="12" class="cards-group">
            <b-col cols="12" class="card-header-base">
              <b-col cols="6" class="card-header-img">
                <img class="team-home" src="../img/manu.png"/>
                <img class="team-away" src="../img/watford.png"/>
              </b-col>
              <b-col cols="6" class="card-header-time">
                <button>1st half</button>
                <p>43'</p>
              </b-col>
            </b-col>
            <b-col cols="12" class="card-body">
              <span>Premier League</span>
              <b-col cols="8" class="teams">
                <p>Manchester United</p>
              </b-col>
              <b-col cols="4" class="score">
                <p>1</p>
              </b-col>
              <b-col cols="8" class="teams">
                <p>Watford</p>
              </b-col>
              <b-col cols="4" class="score">
                <p>2</p>
              </b-col>
            </b-col>
            <b-col cols="12" class="card-point">
              <b-col cols="3" class="rate-button">
                <button id="green-rate">1.28</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button id="red-rate">3.14</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button>2.16</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button id="gray-rate">+48</button>
              </b-col>
            </b-col>
          </b-col>
        </b-col>
        <b-col cols="6" class="cards">
          <b-col cols="12" class="cards-group">
            <b-col cols="12" class="card-header-base">
              <b-col cols="6" class="card-header-img">
                <img class="team-home" src="../img/newcastle.png"/>
                <img class="team-away" src="../img/everton.png"/>
              </b-col>
              <b-col cols="6" class="card-header-time">
                <button>2st half</button>
                <p>64'</p>
              </b-col>
            </b-col>
            <b-col cols="12" class="card-body">
              <span>Premier League</span>
              <b-col cols="8" class="teams">
                <p>Newcastle United</p>
              </b-col>
              <b-col cols="4" class="score">
                <p>1</p>
              </b-col>
              <b-col cols="8" class="teams">
                <p>Everton</p>
              </b-col>
              <b-col cols="4" class="score">
                <p>2</p>
              </b-col>
            </b-col>
            <b-col cols="12" class="card-point">
              <b-col cols="3" class="rate-button">
                <button>1.35</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button>2.10</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button>2.80</button>
              </b-col>
              <b-col cols="3" class="rate-button">
                <button id="gray-rate">+48</button>
              </b-col>
            </b-col>
          </b-col>
        </b-col>
      </b-col>
    </section>
    <section class="casino-base">
      <b-col cols="12" class="casino">
        <b-col cols="12" class="casino-search-bar">
          <b-col cols="6" class="casino-bar-left">
            <h4>Casino</h4>
            <p>Popular Games</p>
          </b-col>
          <b-col cols="6" class="casino-bar-right">
            <input type="text" placeholder="Search Games">
            <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-search" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" d="M10.442 10.442a1 1 0 0 1 1.415 0l3.85 3.85a1 1 0 0 1-1.414 1.415l-3.85-3.85a1 1 0 0 1 0-1.415z"/>
              <path fill-rule="evenodd" d="M6.5 12a5.5 5.5 0 1 0 0-11 5.5 5.5 0 0 0 0 11zM13 6.5a6.5 6.5 0 1 1-13 0 6.5 6.5 0 0 1 13 0z"/>
            </svg>

          </b-col>
        </b-col>
        <div class="games-main">
          <b-col cols="4" class="casino-game-first">
            <img src="../img/contact.png" alt="">
          </b-col>
        <b-col cols="8" class="casino-game">
          <b-col cols="12" class="casino-game">
            <b-col cols="12" class="casino-game-content">
            <b-col cols="3" class="casino-game">
             <img src="../img/MegaMoolah_MGM_300x300 (1).png"/>
            </b-col>
            <b-col cols="6" class="casino-game">
              <img src="../img/BellOfortune_PNG_300x300.png"/>
            </b-col>
            <b-col cols="3" class="casino-game">
              <img src="../img/Starburst_NET_300x300.png"/>
            </b-col>
            </b-col>
          </b-col>
          <b-col cols="12" class="casino-game">
            <b-col cols="12" class="casino-game-content">
              <b-col cols="3" class="casino-game">
                <img src="../img/1564046268324_fireflyfrenzy_PNG_300x300.png"/>
              </b-col>
              <b-col cols="3" class="casino-game">
                <img src="../img/BookOfDead_PNG_300x300.png"/>
              </b-col>
              <b-col cols="3" class="casino-game">
                <img src="../img/WildFalls_PNG_300x300.png"/>
              </b-col>
              <b-col cols="3" class="casino-game">
                <img src="../img/CashSplash_MGM_300x300.png"/>
              </b-col>
            </b-col>

          </b-col>
        </b-col>
        </div>
      </b-col>


    </section>
    <section class="slider-area-base">
      <b-col cols="12" class="news-main-title">
        <h4>News</h4>
        <p>Current Sports news</p>
      </b-col>
    <b-col cols="12" class="slider-area">
        <b-col cols="5" class="slider">
          <b-col cols="12" class="slider-cart-base">
        <div class="slider-cart">
          <div class="date-cart"><p class="date-day">26</p><p class="date-month">OCT</p></div>
          <img src="../img/Layer 1.png"/>
        </div>
        <div class="slider-cart-soccer">
          <img src="../img/soccer-ball copy.png" />
          <p>ICE HOKEY</p>
        </div>
        <div class="slider-cart-description">
          <h5>Will Phoenix's MLS expansion bid rise abo-ve the others project system ?</h5>
          <p>Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
          </b-col>
        </b-col>
      <b-col cols="5" class="slider">
        <b-col cols="12" class="slider-cart-base">
          <div class="slider-cart">
            <div class="date-cart"><p class="date-day">25</p><p class="date-month">OCT</p></div>
            <img src="../img/Layer 2.png"/>
          </div>
          <div class="slider-cart-soccer">
            <img src="../img/soccer-ball copy.png" />
            <p>FOOTBALL</p>
          </div>
          <div class="slider-cart-description">
            <h5>Clemson topples Alabama on last-second touchdown for title</h5>
            <p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam elus...</p>
          </div>
        </b-col>
      </b-col>
      <b-col cols="5" class="slider">
        <b-col cols="12" class="slider-cart-base">
          <div class="slider-cart">
            <div class="date-cart"><p class="date-day">26</p><p class="date-month">OCT</p></div>
            <img src="../img/Layer 2.png"/>
          </div>
          <div class="slider-cart-soccer">
            <img src="../img/soccer-ball copy.png" />
            <p>FOOTBALL</p>
          </div>
          <div class="slider-cart-description">
            <h5>Clemson topples Alabama on last-second touchdown for title</h5>
            <p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam elus...</p>
          </div>
        </b-col>
      </b-col>

    </b-col>
    </section>
    <section class="stats-base">
      <b-col cols="12" class="stats">
        <b-col cols="12" class="stats-main">
          <b-col cols="6" class="stats-league">
            <img src="../img/seria.png" alt="">
            <select id="league">
              <option value="seria">Italia Seria A</option>
              <option value="premier">Premier League</option>
              <option value="super">Super League</option>
            </select>
          </b-col>
          <b-col cols="6" class="board-write">
            <p>Score Board</p>
          </b-col>
<b-col cols="12" class="soccer-table-base">
  <table class="soccer-table">
    <thead>
    <tr class="soccer-table-stats">
      <th class="stats-teams-title">Team</th>
      <th class="stats-title-right">O</th>
      <th class="stats-title-right">P</th>
      <th class="stats-title-right">AV</th>
    </tr>
    </thead>
    <tbody>
    <tr class="soccer-table-stats">
      <td class="team-soccer"><img  class="team-logo" src="../img/juventus.png" alt="">Juventus</td>
      <td class="team-point">8</td>
      <td class="team-point">22</td>
      <td class="team-point">+8</td>
    </tr>
    <tr class="soccer-table-stats">
      <td class="team-soccer"><img  class="team-logo" src="../img/inter.png" alt="">Inter</td>
      <td class="team-point">8</td>
      <td class="team-point">22</td>
      <td class="team-point">+8</td>
    </tr>
    <tr class="soccer-table-stats">
      <td class="team-soccer"><img  class="team-logo" src="../img/atalanta.png" alt="">Atalanta</td>
      <td class="team-point">8</td>
      <td class="team-point">22</td>
      <td class="team-point">+8</td>
    </tr>
    </tbody>
  </table>
<a href="" class="show-all">Show All</a>
</b-col>

      </b-col>
      </b-col>
    </section>
  </div>

</template>


<script>
export default {
  data () {}
  }
</script>

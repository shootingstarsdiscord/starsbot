<h2 class="code-line" data-line-start="0" data-line-end="1"><a id="Unhelpful_guide_to_starsbot_0"></a>Unhelpful guide to stars-bot</h2>
<p class="has-line-data" data-line-start="2" data-line-end="3">Stars bot is a bot created by enigma using the cards created by seolhyunssi and gkprotectionsquad. The trading card bot functions using a currency called “COPE”. If being viewed as html, the links to discord channels may not work.</p>
<h2 class="code-line" data-line-start="4" data-line-end="5"><a id="For_beginners_4"></a>For beginners</h2>
<h4 class="code-line" data-line-start="5" data-line-end="6"><a id="Collecting_COPE_5"></a>Collecting COPE:</h4>
<p class="has-line-data" data-line-start="6" data-line-end="7"><strong>How to see the total amount of cope owned: Use the <code>-stars bal</code> command.</strong></p>
<ol>
<li class="has-line-data" data-line-start="8" data-line-end="9">Join prediction league: Most of the users of the bot participate in the <a href="https://docs.google.com/spreadsheets/d/1JDvGsY31Bl9yINImUFl7Hm6lR3MrQX2Z73f-M9AeBTw/edit#gid=2034814005">predictions league</a></li>
<li class="has-line-data" data-line-start="9" data-line-end="10"><code>-stars daily</code> : using this command gives you 50 COPE everyday in the <a href="https://discord.com/channels/923724446898995310/1134900929850773577"><code>Stars Bot</code></a> forum, resets at 8PM EST.</li>
<li class="has-line-data" data-line-start="10" data-line-end="11"><code>-stars play</code>: guess the player based on the stat in the <a href="https://discord.com/channels/923724446898995310/1163165427485118464"><code>Stars Bot: Guessing Forum</code></a> gives you 10 COPE each day, resets at the same time as the daily cope. Refer: Guessing game</li>
<li class="has-line-data" data-line-start="11" data-line-end="12">Selling cards: Cards can be sold via the market, refer to <code>-stars market</code></li>
<li class="has-line-data" data-line-start="12" data-line-end="13">Find bugs in the bot for 5 COPE!</li>
<li class="has-line-data" data-line-start="13" data-line-end="15"><strong>JOIN THE WEEKLY GAMES SESSION!</strong> (Ping @pghost for more information on the next game session)</li>
</ol>
<h4 class="code-line" data-line-start="15" data-line-end="16"><a id="Collecting_Cards_15"></a>Collecting Cards:</h4>
<ol>
<li class="has-line-data" data-line-start="16" data-line-end="17"><code>-stars buy [silver/gold] [amount]</code>: gives you one silver or gold pack. A silver costs 20 cope. Silvers generally result into 1-7 :star: cards with high probability, with some exceptions. Golds have a higher probability of 7-10 :star: cards and above.</li>
<li class="has-line-data" data-line-start="17" data-line-end="20"><code>-stars buy [event/special]</code>: Special packs with a slightly higher chance of higher rarity cards. Mainly available during events or by using Clown coins [see: Events]<br>
<strong>Silvers are generally recommended for completionists who are just getting used to stars-bot. Golds are recommended for people looking for higher rated cards, eventually as you get used to the bot commands, you will know which pack to pull depending on the card you’re looking for</strong></li>
</ol>
<h4 class="code-line" data-line-start="20" data-line-end="21"><a id="How_to_see_collected_cards_20"></a>How to see collected cards:</h4>
<ol>
<li class="has-line-data" data-line-start="21" data-line-end="22"><code>-stars collection [all/team_name]</code>: displays the collection of cards along with the card_ID and the number of cards available in the collection. The collection can be displayed in full using the parameter all, or for a particular team, for example <code>-stars collection WC</code>.</li>
<li class="has-line-data" data-line-start="22" data-line-end="23"><code>-stars collection dupes</code>: displays the number of duplicate cards in the collection.</li>
<li class="has-line-data" data-line-start="23" data-line-end="25"><code>-stars show [card_ID]</code>: Each card has been given an ID which can be used to see a particular card.</li>
</ol>
<h4 class="code-line" data-line-start="25" data-line-end="26"><a id="Trading_cards_25"></a>Trading Cards:</h4>
<ol>
<li class="has-line-data" data-line-start="26" data-line-end="27"><code>-stars market</code>: Market consists of cards sold by other players. To buy a card use the command <code>-stars marketbuy [sale_ID]</code>. Sale id can be found in the market listing. To sell a card, use the <code>-stars marketsell [card_ID] [amount]</code>.</li>
<li class="has-line-data" data-line-start="27" data-line-end="29"><code>-stars trade [card_trade_ID] [userName] [card_offered_ID]</code>: Trade a card you have (<code>card_trade_ID</code>) with a card from a different user. You can accept a trade using <code>-stars tradeaccept</code></li>
</ol>
<h2 class="code-line" data-line-start="29" data-line-end="30"><a id="For_intermediateadvanced_users_29"></a>For intermediate/advanced users</h2>
<h3 class="code-line" data-line-start="31" data-line-end="32"><a id="Events_31"></a>Events:</h3>
<ol>
<li class="has-line-data" data-line-start="32" data-line-end="43">Guess Bot:<br>
i. Guess Bot is a separate bot created before the TCG bot. The guess bot obtains a player stat at random and the user has to guess the player based on the statistic. More info on which players/matches are included on <code>-stars info guessbot</code><br>
ii. You can obtain 10 COPE every day by playing the guess bot in the <a href="https://discord.com/channels/923724446898995310/1163165427485118464">Stars Bot: Guessing Forum</a> channel.<br>
iii. To initiate a game use <code>-stars play</code><br>
vi. To guess a player use <code>-stars guess [playerName]</code>. For example: <code>-stars guess amy</code>.<br>
iv. If you are unable to guess the player, use <code>-stars hint</code>. Using this command more than once decreases the amount of cope obtained per round, eventually leading to a forfeit.<br>
v. To end or forfeit the game, use <code>-stars forfeit</code>. You will not get any cope for a forfeited round.<br>
vi. The stats and hints disappear after a certain interval of time. Use <code>-stars recap</code> to display the stats and hints again.<br>
vii. If the user who initiates the guessing game does not guess the player, they will earn a certain amount of cope for initiation. This amount will be lesser than the cope obtained for guessing.<br>
viii. To look up the acceptable player names for teams, use <code>-stars lookup [teamName]</code>. If the team name is entered incorrectly, the bot will let you know of the acceptable team names.<br>
ix. If you want to lookup a team privately, use <code>-stars privatelookup</code></li>
</ol>
<ol start="2">
<li class="has-line-data" data-line-start="45" data-line-end="54">
<p class="has-line-data" data-line-start="45" data-line-end="53">Weekly Sets:<br>
i. Each week the bot picks a team at random and picks 5 players 7 :star: and under to be a part of the weekly set.<br>
ii. Bot users can choose to add the 5 players chosen by the bot to their respective collections. To see which cards are a part of the weekly set for the current week and to check progress of your weekly set, use <code>-stars setprogress</code><br>
iii. If a user chooses to add a player, <strong>the player gets removed from the users collection permanently</strong>. You can add in the player using <code>-stars addtoset [cardID]</code><br>
iv. Adding all five players gives the user a Clown coin which can be used to pull a special/event pack.<br>
v. If you complete 4 weekly sets, you will obtain one of the two MVP card at random. At 10 weekly sets completed, you will get the other MVP card. It does not have to be consecutive sets completed.<br>
v. If you are unable complete the set for a particular week, you can either choose to either have your cards returned back to you or have the added cards be converted to XP. The XP can be converted to Clown coins the subsequent week. <strong>The XP does not count towards completed sets required for the MVP cards.</strong><br>
vi. Weekly sets reset on the -stars daily that immediately precedes Wednesday in South Korea. vii. <strong>The MVP cards are UNOBTAINABLE post the end of the current season.</strong></p>
</li>
<li class="has-line-data" data-line-start="54" data-line-end="55">
<p class="has-line-data" data-line-start="54" data-line-end="55">Post season events: Enigma holds events where the droprates of higher rarity cards are increased. Usually it is at the end of the season or sometimes during festivals (Seollal/Chuseok/Christmas/NYE). It might be a good idea to start saving before such events.</p>
</li>
</ol>

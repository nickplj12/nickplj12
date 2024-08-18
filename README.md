# funny css injection
[install this violentmonkey script for funny css injection](https://github.com/thatonepuggo/statue-repo/raw/master/docs/githubcssinjector.user.js)
```css
@@@INJECT_CSS@@@
* {
  font-family: 'Comic Sans MS';
}
@keyframes shake {
  0% { transform: translate(11px, -10px); }
  5% { transform: translate(-27px, 12px); }
  10% { transform: translate(29px, -15px); }
  15% { transform: translate(1px, -17px); }
  20% { transform: translate(-21px, -4px); }
  25% { transform: translate(7px, 19px); }
  30% { transform: translate(-7px, -12px); }
  35% { transform: translate(23px, -18px); }
  40% { transform: translate(21px, -5px); }
  45% { transform: translate(-27px, 27px); }
  50% { transform: translate(17px, -8px); }
  55% { transform: translate(-16px, -18px); }
  60% { transform: translate(2px, 17px); }
  65% { transform: translate(-18px, 2px); }
  70% { transform: translate(-27px, -4px); }
  75% { transform: translate(16px, -10px); }
  80% { transform: translate(14px, -25px); }
  85% { transform: translate(26px, 2px); }
  90% { transform: translate(7px, -16px); }
  95% { transform: translate(8px, -30px); }
  100% { transform: translate(-26px, -15px); }
}
body {
  background-image: url("https://raw.githubusercontent.com/nickplj12/nickplj12/main/spunchbob-sad.gif");
  background-blend-mode: overlay;
}
*:hover {
font-family: "Papyrus", "Comic Sans MS";
}
button:hover {
animation: shake infinite 0.5s steps(1, end);
}
.ContributionCalendar-day {
    fill: var(--color-calendar-graph-day-L4-bg) !important;
    background-color: var(--color-calendar-graph-day-L4-bg) !important;
    outline: 1px solid var(--color-calendar-graph-day-L4-border) !important;
}
@@@END@@@
```

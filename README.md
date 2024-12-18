# Token Logger

⚠️ **Note**: I'm not affiliated with Discord and do not encourage using any of these scripts. Use everything here at your own risk. This is meant for **educational purposes** only and using these codeblocks may result in your account being disabled/terminated.

# Inner workings of Discord

**Disclaimer**: The information provided in this section is obtained through reverse engineering and NOT verified for it's accuracy. Therefore it might be outdated as well.

**My Exclusive Console JS For Discord**

## Scripts

- `Token Logger 1`: Log In Using Token
- `Token Logger 2`: Log In Using Token
<header>
  
# Token Logger

<details>
  <summary>Expand</summary>
 
  ```js
  let token = "Your Token;

function login(token) {
    setInterval(() => {
      document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
      location.reload();
    }, 2500);
  }

login(token);
  ```
</details>



<details>
  <summary>Expand</summary>
 
  ```js
function login(token) {
    setInterval(() => {
        document.body.appendChild(document.createElement`iframe`).contentWindow.localStorage.token = `"${token}"`;
    }, 50);
    setTimeout(() => { location.reload(); }, 2500);
}
login('TOKEN');
  ```

Replace 'TOKEN' with your Token.
</details>

</header>
<header>

# License
Copyright (C) 2024  EndlessAcademy

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
  
</header>

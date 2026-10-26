# Portfolio guide (Taglish)

## Buksan sa Chrome
1. I-extract ang buong folder kung naka-ZIP.
2. I-double-click ang `index.html` o right-click → Open with → Google Chrome. Gumagana ito offline; walang paid hosting, plugin, o install na kailangan.
3. Para ipadala sa client, i-compress/ZIP ang buong folder. Para makita nila online, puwedeng i-host nang libre sa GitHub Pages o Netlify Drop pagkatapos gumawa ng account; hindi kasama ang setup/account dito.

## I-personalize
Buksan ang `index.html` sa Notepad o VS Code. Hanapin ang `QUICK EDIT` comments.

- **Pangalan at headline:** hanapin ang `MKE`, `Mark M.`, `SMARTER`, at palitan ng pangalan at positioning mo.
- **Hero cover:** nasa `assets/hero-cover.png` ang larawan sa itaas ng page. Palitan ang file na iyon ng sarili mong cover (parehong pangalan para walang kailangang baguhin), o palitan ang `assets/hero-cover.png` sa CSS rule na `.hero` kung iba ang filename. I-adjust ang `background-position` para baguhin ang crop.
- **Email/social:** sa ibabang JavaScript block, palitan ang `hello@example.com` at LinkedIn/Facebook URLs. Palitan din ang nakikitang sample text kung gusto.
- **Services, tools, projects:** hanapin ang mga section at palitan ang sample na laman. Gumamit lamang ng tunay na skills, platforms at project results. Huwag ilagay ang client data nang walang pahintulot.
- **Résumé:** ilagay ang PDF sa `assets/Mark-Resume.pdf`, o baguhin ang href ng Download résumé button para tumugma sa pangalan ng file. Kung wala pa, alisin ang button.
- **Kulay/sukat/font:** nasa umpisa ng `<style>` ang `:root` variables. `--blue`, `--violet`, `--cyan`, `--bg`, `--body`, `--title`, `--round` ang mabilis palitan. Para sa mas eksaktong layout, i-edit ang CSS sa parehong file.

## Mga animation
May fade-in habang nag-i-scroll at banayad na galaw ng portrait/cards. Awtomatikong binabawasan ang galaw kung naka-enable ang Reduce Motion sa device.

## Tip sa portfolio content
Ipakita ang problema → ginawa mong automation → tools → resulta (hal. oras na natipid), nang walang sensitibong detalye. Ang mga bilang at project cards ngayon ay sample lamang; palitan o alisin kung hindi pa totoo.

## Libreng online hosting
`index.html` ay static site kaya maaari itong i-host nang libre sa mga provider na may free plan. Ang terms/plans ay maaaring magbago; tingnan ang provider bago mag-publish. Huwag mag-upload ng private client information.


# Yiddish-tools

Tools for writing, editing and publishing texts in Yiddish.

# yi-matveyev.mim

A Yiddish layout for Unix/Linux based on the traditional typewriter layout, which also serves as the base of modern Hebrew layouts. Unlike most other Yiddish layouts, which are either phonetical or based on randomly chosen ligature assignments, this method takes into consideration frequency of ligatures in actual Yiddish texts. 

For the sake of compatibility with some software, especially Adobe Indesign (proprietary and non-existent under Unix, but still broadly considered an industry standand), Yiddish ligatures are provided as character combinations and not as single Unicode characters. In some cases such rendering is beneficial for Scribus too.

# yi-matveyev-alt.mim

In some environments, the Super key may not work properly. The alternative layout **yi-matveyev-alt.mim** uses Alt instead of Super. In some environments the Super key is reserved for something entirely different or simply ignored. The one with Alt that I am currectly using was tested with Ibus on Plasma and LXDE.

To install both layouts, put the files in your m17n database directory and restart your Ibus or Scim. For Ibus, you can also run the following command:

ibus-daemon -d --xim --cache refresh

# LembergYM-Medium.ttf

An old Yiddish semi-cursive font (**vaybertaytsh** or **mashket**) bases on the 1863 Lemberg edition of the book *Nakhles Tsvi*. Contains only Jewish letters.

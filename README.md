# Žintis tyrimas
Šis projektas turėtų leisti paprastai suvesti organizmo metabolizmo nukrypimo tyrimo duomenis internetiniame puslapyje ir duoti atsakymą apie organizmo būklę bei kitą informaciją (daugiau zintis.lt arba https://www.facebook.com/zintis.lt/). Puslapyje turėtų būti nurodyta visa tyrimo eiga ir prie tų žingsnių, kurie reikalauja duomenų, turėtų būti laukeliai (šiuo atveju Bokeh TextInput), į kuriuos suvedus duomenis, automatiškai grafikuose atsispindėtų organimzo nukrypimai ir (galbūt), pateiktos visos reikiamos išvados be žmogaus įsikišimo.  

ls main*.py | entr -p -r -s "bokeh serve --show main.py"


![Alt Text](https://github.com/AndrejusAnto/zintistyrimas/blob/master/demo.gif)

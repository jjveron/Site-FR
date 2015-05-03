Intro.=[Bit/Acte/Accord_Intro.md]

Fin.=[Bit/Acte/Accord_Fin.md]

Attach.=[Bit/Attach]
  
Model.Root={DocCorp}

DocCorp={Doc}

Doc=<font color="grey">{MessagePourUtilisateur}</font><center><h4>{EnTete.Sec}</h4></center>{Intro.Sec}<br>{xlist}<br>{Fin.Sec}{Attach.Sec} 

EnTete.Sec={Ti}

xlist={Olist}

Olist=<ol><li>{Secs}</li></ol>

null=<b></b>

=[Bit/Acte/Mots_Base.md]
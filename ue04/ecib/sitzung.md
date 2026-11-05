# Repository-Inhalt und eigene Dateien

**Session ID:** ses_e54eac494ffeGDoqPi9onho2K1
**Created:** 5.11.2026, 10:40:57
**Updated:** 5.11.2026, 10:41:41

---

## User

Was liegt in diesem Repository, und welche Dateien stammen von mir?

---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git branch --show-current; git status --short; git log --oneline -10"
}
```

ue04-ecib
b5dbd3a Ü2: Ergebnisse von thm-nos (#400)
122ab21 Ergebnisse der Phasen ergänzen (#396)
fcf17f4 Übung 2: Ergebnisse von pz01 (#330)
babf65e Ue02 real (#322)
bf88cc9 Übung 2 ivlbs (#311)
8cfd580 Übung 2: Formatierung der Gesprächsnotiz korrigiert (#286)
baaa2b8 Ergebnisse der Phasen ergänzt in phasenplan.md (#284)
c55409f Übung 2 : Ergebnisse von akyf (#283)
9db8067 Ue02 zsh (#281)
724bbb5 Übung 2: Ergebnisse von nohl (#280)


**Tool: read**

**Input:**
```json
{
  "path": "D:\\Git\\thm_wk-1208_softwaretechnik-uebungen\\README.md"
}
```

Read file D:\Git\thm_wk-1208_softwaretechnik-uebungen\README.md, lines 1-74
1: # Softwaretechnik — Übungsrepository
2: 
3: Dieses Repository gehört zu den Übungen der Veranstaltung **Softwaretechnik**
4: (THM, Campus Friedberg, Fachbereich MND). Hier reichen Sie ein, was in den
5: Übungen entsteht — auf dem Weg, auf dem in Softwareprojekten gearbeitet wird:
6: über einen eigenen Fork, einen Branch und einen Pull Request.
7: 
8: ## Aufbau
9: 
10: Jede Übung hat ein eigenes Verzeichnis mit einer eigenen `README.md`, die
11: sagt, was dort einzureichen ist.
12: 
13: | Verzeichnis | Übung |
14: |---|---|
15: | [`ue01/`](ue01/) | Erste Schritte mit Git und GitHub |
16: | [`ue02/`](ue02/) | Das Projektmodell am Fall |
17: | [`ue03/`](ue03/) | Anforderungen an den Terminplaner |
18: | [`ue04/`](ue04/) | Einen Coding Agent einrichten |
19: 
20: ## So reichen Sie etwas ein
21: 
22: 1. Legen Sie einmalig einen **Fork** dieses Repositorys an und **klonen** Sie
23:    ihn auf Ihren Rechner.
24: 2. Legen Sie für jedes Vorhaben einen eigenen **Branch** an.
25: 3. Halten Sie Ihre Änderungen als **Commits** fest und übertragen Sie sie per
26:    **Push** in Ihren Fork.
27: 4. Stellen Sie einen **Pull Request** an dieses Repository.
28: 
29: Den Weg Schritt für Schritt beschreibt das
30: [Übungsblatt zur Übung 1](https://carstenlucke.github.io/thm_wk-1208_softwaretechnik/ue01-git-github/).
31: 
32: ## Vor jeder weiteren Übung
33: 
34: Dieses Repository wächst mit jeder Übung. Bringen Sie vorher Ihren Fork und
35: Ihren Rechner auf den neuen Stand:
36: 
37: 1. Klicken Sie auf der Startseite Ihres Forks auf **Sync fork → Update
38:    branch**.
39: 2. Holen Sie den neuen Stand aus dem Fork auf Ihren Rechner:
40: 
41:    ```console
42:    $ git switch main
43:    $ git pull
44:    ```
45: 
46: Den Branch für die neue Übung zweigen Sie erst danach ab.
47: 
48: ## Spielregeln
49: 
50: - **Ihr GitHub-Benutzername als Kennung.** Ihre Datei- und Verzeichnisnamen
51:   sowie Ihre Branches tragen Ihren GitHub-Benutzernamen, und zwar in
52:   Kleinbuchstaben: Aus `MMustermann` wird `mmustermann`. Anders als ein
53:   selbst gewähltes Kürzel ist er eindeutig, und er steht ohnehin an jedem
54:   Pull Request. Ihren Benutzernamen sehen Sie auf GitHub, wenn Sie oben
55:   rechts auf Ihr Profilbild klicken.
56: - **Öffentlich ist mehr als der Benutzername.** In jedem Commit stehen Name
57:   und E-Mail-Adresse aus Ihrer Git-Einrichtung. Wie Sie Ihre Adresse
58:   verbergen, steht in
59:   [Aufgabe 0 des Übungsblatts](https://carstenlucke.github.io/thm_wk-1208_softwaretechnik/ue01-git-github/#aufgabe-0--einrichten).
60:   Schreiben Sie auch in Ihre Dateien nichts, was nicht jeder lesen darf —
61:   keine Matrikelnummer, keine Anschrift.
62: - **Nur eigene Dateien.** Sie ändern ausschließlich, was Sie selbst angelegt
63:   haben; Vorlagen und die Dateien anderer bleiben unberührt. So kommen sich
64:   die Pull Requests nicht in die Quere.
65: - **Nicht auf `main` arbeiten.** `main` Ihres Forks folgt allein dem Stand
66:   dieses Repositorys; nur so lässt er sich später abgleichen.
67: - **Ein Anliegen je Pull Request**, mit einem Titel, der sagt, was sich
68:   ändert.
69: - **Aussagekräftige Commit-Nachrichten**, etwa `Steckbrief für mmustermann anlegen`.
70: 
71: Arbeiten Sie mit einem KI-Agenten, gelten die Spielregeln auch für ihn. Die
72: Datei [`AGENTS.md`](AGENTS.md) fasst sie für Agenten zusammen; opencode und
73: andere Coding Agents lesen sie, wenn sie in diesem Repository gestartet
74: werden.

---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git ls-tree -r --name-only HEAD | Select-String -Pattern '^(ue0[1-4])/' | ForEach-Object { $_.Line }"
}
```

ue01/README.md
ue01/steckbriefe/AF.md
ue01/steckbriefe/AR.md
ue01/steckbriefe/Agub.md
ue01/steckbriefe/Anas23088.md
ue01/steckbriefe/Aza.md
ue01/steckbriefe/Bblj09.md
ue01/steckbriefe/Fahm.md
ue01/steckbriefe/HussainButt7.md
ue01/steckbriefe/IY69.md
ue01/steckbriefe/Lpr.md
ue01/steckbriefe/MK.md
ue01/steckbriefe/NN.md
ue01/steckbriefe/NUAli.md
ue01/steckbriefe/Smu.md
ue01/steckbriefe/TariqK2004.md
ue01/steckbriefe/Tiger.md
ue01/steckbriefe/Z-266.md
ue01/steckbriefe/ZahraGit12.md
ue01/steckbriefe/_beispiel.md
ue01/steckbriefe/_vorlage.md
ue01/steckbriefe/aalg.md
ue01/steckbriefe/aayd.md
ue01/steckbriefe/adni.md
ue01/steckbriefe/agbr.md
ue01/steckbriefe/ahyi.md
ue01/steckbriefe/akyf.md
ue01/steckbriefe/ale563.md
ue01/steckbriefe/anddun.md
ue01/steckbriefe/andel0.md
ue01/steckbriefe/anpa.md
ue01/steckbriefe/anushka.md
ue01/steckbriefe/asi.md
ue01/steckbriefe/asng24.md
ue01/steckbriefe/athr.md
ue01/steckbriefe/avon507.md
ue01/steckbriefe/azm96.md
ue01/steckbriefe/bima.md
ue01/steckbriefe/bunter95.md
ue01/steckbriefe/cms.md
ue01/steckbriefe/datr03.md
ue01/steckbriefe/davn68.md
ue01/steckbriefe/dhfn1611.md
ue01/steckbriefe/div.md
ue01/steckbriefe/dlm28.md
ue01/steckbriefe/dmal2004.md
ue01/steckbriefe/dmmh1710.md
ue01/steckbriefe/dsc.md
ue01/steckbriefe/dsch.md
ue01/steckbriefe/dszp.md
ue01/steckbriefe/ecib.md
ue01/steckbriefe/ekes.md
ue01/steckbriefe/emalj.md
ue01/steckbriefe/emrano.md
ue01/steckbriefe/en7-mj.md
ue01/steckbriefe/ezen.md
ue01/steckbriefe/flk.md
ue01/steckbriefe/fortnitepro.md
ue01/steckbriefe/fpz.md
ue01/steckbriefe/hams.md
ue01/steckbriefe/hfdr12.md
ue01/steckbriefe/hjri.md
ue01/steckbriefe/iaa.md
ue01/steckbriefe/iesp.md
ue01/steckbriefe/ilias04j.md
ue01/steckbriefe/ivlbs.md
ue01/steckbriefe/janp.md
ue01/steckbriefe/jat01.md
ue01/steckbriefe/javu.md
ue01/steckbriefe/jemy.md
ue01/steckbriefe/jk04.md
ue01/steckbriefe/jp26.md
ue01/steckbriefe/jsug.md
ue01/steckbriefe/jvng.md
ue01/steckbriefe/kraz.md
ue01/steckbriefe/lebr.md
ue01/steckbriefe/lkrs.md
ue01/steckbriefe/lom.md
ue01/steckbriefe/lpr2.md
ue01/steckbriefe/lswl60.md
ue01/steckbriefe/mabl.md
ue01/steckbriefe/masalabyte.md
ue01/steckbriefe/maxbarrosschauer.md
ue01/steckbriefe/mbgrn04.md
ue01/steckbriefe/mduc.md
ue01/steckbriefe/meq.md
ue01/steckbriefe/mf23.md
ue01/steckbriefe/mjab.md
ue01/steckbriefe/mjas.md
ue01/steckbriefe/mken.md
ue01/steckbriefe/mkon.md
ue01/steckbriefe/mks24.md
ue01/steckbriefe/mnag.md
ue01/steckbriefe/mosm.md
ue01/steckbriefe/mpal.md
ue01/steckbriefe/mskk15.md
ue01/steckbriefe/mu.md
ue01/steckbriefe/mw.md
ue01/steckbriefe/my55.md
ue01/steckbriefe/nblh.md
ue01/steckbriefe/ngh.md
ue01/steckbriefe/nicolino.md
ue01/steckbriefe/nko.md
ue01/steckbriefe/nly50.md
ue01/steckbriefe/nohl.md
ue01/steckbriefe/onzj.md
ue01/steckbriefe/oubou.md
ue01/steckbriefe/pdam.md
ue01/steckbriefe/peng.md
ue01/steckbriefe/pgml.md
ue01/steckbriefe/pz01.md
ue01/steckbriefe/qdb.md
ue01/steckbriefe/qho.md
ue01/steckbriefe/real.md
ue01/steckbriefe/renn.md
ue01/steckbriefe/sahmad.md
ue01/steckbriefe/sahmed.md
ue01/steckbriefe/sam.md
ue01/steckbriefe/sazy1.md
ue01/steckbriefe/sd99.md
ue01/steckbriefe/shiva.md
ue01/steckbriefe/skrl78.md
ue01/steckbriefe/skt435.md
ue01/steckbriefe/slr63.md
ue01/steckbriefe/snab.md
ue01/steckbriefe/sngu.md
ue01/steckbriefe/sshj44.md
ue01/steckbriefe/ssng61.md
ue01/steckbriefe/stmx.md
ue01/steckbriefe/tcam.md
ue01/steckbriefe/thng.md
ue01/steckbriefe/tnd.md
ue01/steckbriefe/tngan.md
ue01/steckbriefe/trry.md
ue01/steckbriefe/ttpr21.md
ue01/steckbriefe/tyfncc.md
ue01/steckbriefe/uk.md
ue01/steckbriefe/uwar.md
ue01/steckbriefe/val.md
ue01/steckbriefe/vic26.md
ue01/steckbriefe/virus.md
ue01/steckbriefe/vkab.md
ue01/steckbriefe/wnga.md
ue01/steckbriefe/yamekk.md
ue01/steckbriefe/ygue.md
ue01/steckbriefe/ykar.md
ue01/steckbriefe/yoibr42.md
ue01/steckbriefe/ysbi82.md
ue01/steckbriefe/zc.md
ue01/steckbriefe/zcbn.md
ue01/steckbriefe/zcoel.md
ue01/steckbriefe/zomj.md
ue02/Agub/notiz.md
ue02/Agub/phasenplan.md
ue02/Agub/rollen.md
ue02/Agub/spezifikation.md
ue02/IY69/notiz.md
ue02/IY69/phasenplan.md
ue02/IY69/spezifikation.md
ue02/Lpr/notiz.md
ue02/Lpr/phasenplan.md
ue02/Lpr/spezifikation.md
ue02/NN/notiz.md
ue02/NN/phasenplan.md
ue02/NN/spezifikation.md
ue02/NUAli/notiz.md
ue02/NUAli/phasenplan.md
ue02/NUAli/spezifikation.md
ue02/README.md
ue02/TariqK2004/notiz.md
ue02/TariqK2004/phasenplan.md
ue02/TariqK2004/spezifikation.md
ue02/_vorlage/notiz.md
ue02/_vorlage/spezifikation.md
ue02/_zugabe/rollen.md
ue02/aayd/notiz.md
ue02/aayd/phasenplan.md
ue02/aayd/spezifikation.md
ue02/abdu113/notiz.md
ue02/abdu113/phasenplan.md
ue02/abdu113/spezifikation.md
ue02/af/notiz.md
ue02/af/phasenplan.md
ue02/af/spezifikation.md
ue02/agbr/notiz.md
ue02/agbr/phasenplan.md
ue02/agbr/spezifikation.md
ue02/ahyi/notiz.md
ue02/ahyi/phasenplan.md
ue02/ahyi/spezifikation.md
ue02/akyf/notiz.md
ue02/akyf/phasenplan.md
ue02/akyf/spezifikation.md
ue02/anas23088/notiz.md
ue02/anas23088/phasenplan.md
ue02/anas23088/rollen.md
ue02/anas23088/spezifikation.md
ue02/anddun/notiz.md
ue02/anddun/phasenplan.md
ue02/anddun/spezifikation.md
ue02/andel0/notiz.md
ue02/andel0/phasenplan.md
ue02/andel0/spezifikation.md
ue02/anpa/notiz.md
ue02/anpa/phasenplan.md
ue02/anpa/rollen.md
ue02/anpa/spezifikation.md
ue02/anushka/notiz.md
ue02/anushka/phasenplan.md
ue02/anushka/rollen.md
ue02/anushka/spezifikation.md
ue02/athr/notiz.md
ue02/athr/phasenplan.md
ue02/athr/spezifikation.md
ue02/avon507/notiz.md
ue02/avon507/phasenplan.md
ue02/avon507/spezifikation.md
ue02/ayue/notiz.md
ue02/ayue/phasenplan.md
ue02/ayue/spezifikation.md
ue02/bblj09/notiz.md
ue02/bblj09/phasenplan.md
ue02/bblj09/spezifikation.md
ue02/bima/notiz.md
ue02/bima/phasenplan.md
ue02/bima/spezifikation.md
ue02/datr03/notiz.md
ue02/datr03/phasenplan.md
ue02/datr03/spezifikation.md
ue02/div/notiz.md
ue02/div/phasenplan.md
ue02/div/rollen.md
ue02/div/spezifikation.md
ue02/dlm28/notiz.md
ue02/dlm28/phasenplan.md
ue02/dlm28/spezifikation.md
ue02/dmmh1710/notiz.md
ue02/dmmh1710/phasenplan.md
ue02/dmmh1710/spezifikation.md
ue02/dsc/notiz.md
ue02/dsc/phasenplan.md
ue02/dsc/spezifikation.md
ue02/dsch/notiz.md
ue02/dsch/phasenplan.md
ue02/dsch/spezifikation.md
ue02/dszp/notiz.md
ue02/dszp/phasenplan.md
ue02/dszp/spezifikation.md
ue02/emrano/notiz.md
ue02/emrano/phasenplan.md
ue02/emrano/spezifikation.md
ue02/en7-mj/notiz.md
ue02/en7-mj/phasenplan.md
ue02/en7-mj/spezifikation.md
ue02/ezen/notiz.md
ue02/ezen/phasenplan.md
ue02/ezen/spezifikation.md
ue02/fahm/notiz.md
ue02/fahm/phasenplan.md
ue02/fahm/spezifikation.md
ue02/flk/notiz.md
ue02/flk/phasenplan.md
ue02/flk/spezifikation.md
ue02/fortnitepro/notiz.md
ue02/fortnitepro/phasenplan.md
ue02/fortnitepro/spezifikation.md
ue02/hams/notiz.md
ue02/hams/phasenplan.md
ue02/hams/spezifikation.md
ue02/hfdr12/notiz.md
ue02/hfdr12/phasenplan.md
ue02/hfdr12/spezifikation.md
ue02/iaa/notiz.md
ue02/iaa/phasenplan.md
ue02/iaa/spezifikation.md
ue02/iesp/notiz.md
ue02/iesp/phasenplan.md
ue02/iesp/spezifikation.md
ue02/ilias04j/notiz.md
ue02/ilias04j/phasenplan.md
ue02/ilias04j/spezifikation.md
ue02/ivlbs/notiz.md
ue02/ivlbs/phasenplan.md
ue02/ivlbs/spezifikation.md
ue02/janp/notiz.md
ue02/janp/phasenplan.md
ue02/janp/rollen.md
ue02/janp/spezifikation.md
ue02/javu11/notiz.md
ue02/javu11/phasenplan.md
ue02/javu11/rollen.md
ue02/javu11/spezifikation.md
ue02/jemy/notiz.md
ue02/jemy/phasenplan.md
ue02/jemy/rollen.md
ue02/jemy/spezifikation.md
ue02/jp26/notiz.md
ue02/jp26/phasenplan.md
ue02/jp26/spezifikation.md
ue02/jsug/notiz.md
ue02/jsug/phasenplan.md
ue02/jsug/spezifikation.md
ue02/jvng/notiz.md
ue02/jvng/rollen.md
ue02/jvng/spezifikation.md
ue02/kraz/notiz.md
ue02/kraz/phasenplan.md
ue02/kraz/spezifikation.md
ue02/lebr/notiz.md
ue02/lebr/phasenplan.md
ue02/lebr/spezifikation.md
ue02/lom/notiz.md
ue02/lom/phasenplan.md
ue02/lom/spezifikation.md
ue02/mabl/notiz.md
ue02/mabl/phasenplan.md
ue02/mabl/spezifikation.md
ue02/masalabyte/notiz.md
ue02/masalabyte/phasenplan.md
ue02/masalabyte/spezifikation.md
ue02/maxbarrosschauer/notiz.md
ue02/maxbarrosschauer/phasenplan.md
ue02/maxbarrosschauer/rollen.md
ue02/maxbarrosschauer/spezifikation.md
ue02/mbgrn04/notiz.md
ue02/mbgrn04/phasenplan.md
ue02/mbgrn04/spezifikation.md
ue02/mduc/notiz.md
ue02/mduc/phasenplan.md
ue02/mduc/spezifikation.md
ue02/meq/notiz.md
ue02/meq/phasenplan.md
ue02/meq/rollen.md
ue02/meq/spezifikation.md
ue02/mf23/notiz.md
ue02/mf23/phasenplan.md
ue02/mf23/spezifikation.md
ue02/mjab/notiz.md
ue02/mjab/phasenplan.md
ue02/mjab/spezifikation.md
ue02/mjas/notiz.md
ue02/mjas/phasenplan.md
ue02/mjas/spezifikation.md
ue02/mk/phasenplan.md
ue02/mkon/notiz.md
ue02/mkon/phasenplan.md
ue02/mkon/spezifikation.md
ue02/mpal/notiz.md
ue02/mpal/phasenplan.md
ue02/mpal/spezifikation.md
ue02/mu/notiz.md
ue02/mu/phasenplan.md
ue02/mu/spezifikation.md
ue02/mw/notiz.md
ue02/mw/phasenplan.md
ue02/mw/spezifikation.md
ue02/my55/notiz.md
ue02/my55/phasenplan.md
ue02/my55/spezifikation.md
ue02/ngh/notiz.md
ue02/ngh/phasenplan.md
ue02/ngh/spezifikation.md
ue02/nicolino/notiz.md
ue02/nicolino/phasenplan.md
ue02/nicolino/spezifikation.md
ue02/nko/notiz.md
ue02/nko/phasenplan.md
ue02/nko/spezifikation.md
ue02/nly50/notiz.md
ue02/nly50/phasenplan.md
ue02/nly50/spezifikation.md
ue02/nohl/notiz.md
ue02/nohl/phasenplan.md
ue02/nohl/spezifikation.md
ue02/oubou/notiz.md
ue02/oubou/phasenplan.md
ue02/oubou/spezifikation.md
ue02/pdam/notiz.md
ue02/pdam/phasenplan.md
ue02/pdam/spezifikation.md
ue02/pgml/notiz.md
ue02/pgml/phasenplan.md
ue02/pgml/spezifikation.md
ue02/pz01/notiz.md
ue02/pz01/phasenplan.md
ue02/pz01/spezifikation.md
ue02/qdb/notiz.md
ue02/qdb/phasenplan.md
ue02/qdb/rollen.md
ue02/qdb/spezifikation.md
ue02/qho/notiz.md
ue02/qho/phasenplan.md
ue02/qho/spezifikation.md
ue02/real/notiz.md
ue02/real/phasenplan.md
ue02/real/spezifikation.md
ue02/renn/notiz.md
ue02/renn/phasenplan.md
ue02/renn/spezifikation.md
ue02/sahmad/notiz.md
ue02/sahmad/phasenplan.md
ue02/sahmad/spezifikation.md
ue02/sahmed/notiz.md
ue02/sahmed/phasenplan.md
ue02/sahmed/rollen.md
ue02/sahmed/spezifikation.md
ue02/sam/notiz.md
ue02/sam/phasenplan.md
ue02/sam/spezifikation.md
ue02/skrl78/notiz.md
ue02/skrl78/phasenplan.md
ue02/skrl78/rollen.md
ue02/skrl78/spezifikation.md
ue02/skt435/notiz.md
ue02/skt435/spezifikation.md
ue02/snab/notiz.md
ue02/snab/phasenplan.md
ue02/snab/spezifikation.md
ue02/sngu/notiz.md
ue02/sngu/phasenplan.md
ue02/sngu/spezifikation.md
ue02/ssda78/notiz.md
ue02/ssda78/spezifikation.md
ue02/sshj44/notiz.md
ue02/sshj44/phasenplan.md
ue02/sshj44/spezifikation.md
ue02/ssng61/notiz.md
ue02/ssng61/spezifikation.md
ue02/stmx/notiz.md
ue02/stmx/phasenplan.md
ue02/stmx/spezifikation.md
ue02/talh/notiz.md
ue02/talh/phasenplan.md
ue02/talh/rollen.md
ue02/talh/spezifikation.md
ue02/tcam/notiz.md
ue02/tcam/phasenplan.md
ue02/tcam/spezifikation.md
ue02/thm-nos/notiz.md
ue02/thm-nos/phasenplan.md
ue02/thm-nos/spezifikation.md
ue02/thng/notiz.md
ue02/thng/phasenplan.md
ue02/thng/spezifikation.md
ue02/tiger/notiz.md
ue02/tiger/phasenplan.md
ue02/tiger/spezifikation.md
ue02/tnd/notiz.md
ue02/tnd/phasenplan.md
ue02/tnd/spezifikation.md
ue02/tngan/notiz.md
ue02/tngan/phasenplan.md
ue02/tngan/spezifikation.md
ue02/trry/notiz.md
ue02/trry/phasenplan.md
ue02/trry/rollen.md
ue02/trry/spezifikation.md
ue02/ttpr21/notiz.md
ue02/ttpr21/phasenplan.md
ue02/ttpr21/spezifikation.md
ue02/tyfncc/notiz.md
ue02/tyfncc/phasenplan.md
ue02/tyfncc/rollen.md
ue02/tyfncc/spezifikation.md
ue02/uwar/notiz.md
ue02/uwar/phasenplan.md
ue02/uwar/spezifikation.md
ue02/vic26/notiz.md
ue02/vic26/phasenplan.md
ue02/vic26/spezifikation.md
ue02/virus/notiz.md
ue02/virus/phasenplan.md
ue02/virus/spezifikation.md
ue02/wnga/notiz.md
ue02/wnga/phasenplan.md
ue02/wnga/rollen.md
ue02/wnga/spezifikation.md
ue02/ygue/notiz.md
ue02/ygue/phasenplan.md
ue02/ygue/spezifikation.md
ue02/ysbi82/notiz.md
ue02/ysbi82/spezifikation.md
ue02/zcbn/notiz.md
ue02/zcbn/phasenplan.md
ue02/zcbn/spezifikation.md
ue02/zcoel/notiz.md
ue02/zcoel/phasenplan.md
ue02/zcoel/spezifikation.md
ue02/zsh/notiz.md
ue02/zsh/phasenplan.md
ue02/zsh/spezifikation.md
ue03/IY69/anforderungen.md
ue03/IY69/kontext.md
ue03/IY69/zuordnung.md
ue03/Lpr/anforderungen.md
ue03/Lpr/kontext.md
ue03/Lpr/zuordnung.md
ue03/MK/anforderungen.md
ue03/MK/kontext.md
ue03/MK/zuordnung.md
ue03/NN/anforderungen.md
ue03/NN/kontext.md
ue03/NN/zuordnung.md
ue03/NUAli/anforderungen.md
ue03/NUAli/kontext.md
ue03/NUAli/zuordnung.md
ue03/README.md
ue03/TariqK2004/anforderungen.md
ue03/TariqK2004/kontext.md
ue03/TariqK2004/zuordnung.md
ue03/_vorlage/anforderungen.md
ue03/_vorlage/kontext.md
ue03/aayd/anforderungen.md
ue03/aayd/kontext.md
ue03/aayd/zuordnung.md
ue03/af/anforderungen.md
ue03/af/kontext.md
ue03/af/zuordnung.md
ue03/agbr/anforderungen.md
ue03/agbr/kontext.md
ue03/agbr/zuordnung.md
ue03/ahyi/anforderungen.md
ue03/ahyi/kontext.md
ue03/ahyi/zuordnung.md
ue03/akyf/anforderungen.md
ue03/akyf/kontext.md
ue03/akyf/zuordnung.md
ue03/anas23088/anforderungen.md
ue03/anas23088/kontext.md
ue03/anas23088/zuordnung.md
ue03/anddun/anforderungen.md
ue03/anddun/kontext.md
ue03/anddun/zuordnung.md
ue03/andel0/anforderungen.md
ue03/andel0/kontext.md
ue03/andel0/zuordnung.md
ue03/anpa/anforderungen.md
ue03/anpa/kontext.md
ue03/anpa/zuordnung.md
ue03/anushka/anforderungen.md
ue03/anushka/kontext.md
ue03/anushka/zuordnung.md
ue03/avon507/anforderungen.md
ue03/avon507/kontext.md
ue03/avon507/zuordnung.md
ue03/ayue/anforderungen.md
ue03/ayue/kontext.md
ue03/ayue/zuordnung.md
ue03/azm96/anforderungen.md
ue03/azm96/kontext.md
ue03/azm96/zuordnung.md
ue03/bblj09/anforderungen.md
ue03/bblj09/kontext.md
ue03/bblj09/zuordnung.md
ue03/bogh233/anforderungen.md
ue03/bogh233/kontext.md
ue03/bogh233/zuordnung.md
ue03/cms/anforderungen.md
ue03/cms/kontext.md
ue03/cms/zuordnung.md
ue03/davn68/anforderungen.md
ue03/davn68/kontext.md
ue03/davn68/zuordnung.md
ue03/dlm28/anforderungen.md
ue03/dlm28/kontext.md
ue03/dlm28/zuordnung.md
ue03/dmmh1710/anforderungen.md
ue03/dmmh1710/kontext.md
ue03/dmmh1710/zuordnung.md
ue03/dsch/anforderungen.md
ue03/dsch/kontext.md
ue03/dsch/zuordnung.md
ue03/ecib/anforderungen.md
ue03/ecib/kontext.md
ue03/ecib/zuordnung.md
ue03/emrano/anforderungen.md
ue03/emrano/kontext.md
ue03/emrano/zuordnung.md
ue03/en7-mj/anforderungen.md
ue03/en7-mj/kontext.md
ue03/en7-mj/zuordnung.md
ue03/ezen/anforderungen.md
ue03/ezen/kontext.md
ue03/ezen/zuordnung.md
ue03/fahm/anforderungen.md
ue03/fahm/kontext.md
ue03/fahm/zuordnung.md
ue03/flk/anforderungen.md
ue03/flk/kontext.md
ue03/flk/zuordnung.md
ue03/hfdr12/anforderungen.md
ue03/hfdr12/kontext.md
ue03/hfdr12/zuordnung.md
ue03/iaa/anforderungen.md
ue03/iaa/kontext.md
ue03/iaa/zuordnung.md
ue03/ilias04j/anforderungen.md
ue03/ilias04j/kontext.md
ue03/ilias04j/zuordnung.md
ue03/janp/anforderungen.md
ue03/janp/kontext.md
ue03/janp/zuordnung.md
ue03/javu/anforderungen.md
ue03/javu/kontext.md
ue03/javu/zuordnung.md
ue03/jemy/anforderungen.md
ue03/jemy/kontext.md
ue03/jemy/zuordnung.md
ue03/jsug/anforderungen.md
ue03/jsug/kontext.md
ue03/jsug/zuordnung.md
ue03/jvng/anforderungen.md
ue03/jvng/kontext.md
ue03/jvng/zuordnung.md
ue03/kraz/anforderungen.md
ue03/kraz/kontext.md
ue03/kraz/zuordnung.md
ue03/lkrs/anforderungen.md
ue03/lkrs/kontext.md
ue03/lkrs/zuordnung.md
ue03/lom/anforderungen.md
ue03/lom/kontext.md
ue03/lom/zuordnung.md
ue03/masalabyte/anforderungen.md
ue03/masalabyte/kontext.md
ue03/masalabyte/zuordnung.md
ue03/maxbarrosschauer/anforderungen.md
ue03/maxbarrosschauer/kontext.md
ue03/maxbarrosschauer/zuordnung.md
ue03/mduc/anforderungen.md
ue03/mduc/kontext.md
ue03/mduc/zuordnung.md
ue03/meq/anforderungen.md
ue03/meq/kontext.md
ue03/meq/zuordnung.md
ue03/mjab/anforderungen.md
ue03/mjab/kontext.md
ue03/mjab/zuordnung.md
ue03/mken/anforderungen.md
ue03/mken/kontext.md
ue03/mken/zuordnung.md
ue03/mkon/anforderungen.md
ue03/mkon/kontext.md
ue03/mkon/zuordnung.md
ue03/moh/anforderungen.md
ue03/moh/kontext.md
ue03/moh/zuordnung.md
ue03/mpal/anforderungen.md
ue03/mpal/kontext.md
ue03/mpal/zuordnung.md
ue03/mskk15/anforderungen.md
ue03/mskk15/kontext.md
ue03/mu/anforderungen.md
ue03/mu/kontext.md
ue03/mu/zuordnung.md
ue03/mw/anforderungen.md
ue03/mw/kontext.md
ue03/mw/zuordnung.md
ue03/my55/anforderungen.md
ue03/my55/kontext.md
ue03/my55/zuordnung.md
ue03/nicolino/anforderungen.md
ue03/nicolino/kontext.md
ue03/nicolino/zuordnung.md
ue03/nko/anforderungen.md
ue03/nko/kontext.md
ue03/nko/zuordnung.md
ue03/nly50/anforderungen.md
ue03/nly50/kontext.md
ue03/nly50/zuordnung.md
ue03/nohl/anforderungen.md
ue03/nohl/kontext.md
ue03/nohl/zuordnung.md
ue03/onzj/anforderungen.md
ue03/onzj/kontext.md
ue03/onzj/zuordnung.md
ue03/oubou/anforderungen.md
ue03/oubou/kontext.md
ue03/oubou/zuordnung.md
ue03/pdam/anforderungen.md
ue03/pdam/kontext.md
ue03/pdam/zuordnung.md
ue03/pgml/anforderungen.md
ue03/pgml/kontext.md
ue03/pgml/zuordnung.md
ue03/pz01/anforderungen.md
ue03/pz01/kontext.md
ue03/pz01/zuordnung.md
ue03/qho/anforderungen.md
ue03/qho/kontext.md
ue03/qho/zuordnung.md
ue03/real/anforderungen.md
ue03/real/kontext.md
ue03/real/zuordnung.md
ue03/sahmad/anforderungen.md
ue03/sahmad/kontext.md
ue03/sahmad/zuordnung.md
ue03/sahmed/anforderungen.md
ue03/sahmed/kontext.md
ue03/sahmed/zuordnung.md
ue03/sam/anforderungen.md
ue03/sam/kontext.md
ue03/sam/zuordnung.md
ue03/skrl78/anforderungen.md
ue03/skrl78/kontext.md
ue03/skrl78/zuordnung.md
ue03/snab/anforderungen.md
ue03/snab/kontext.md
ue03/snab/zuordnung.md
ue03/sngu/anforderungen.md
ue03/sngu/kontext.md
ue03/sngu/zuordnung.md
ue03/sraks/anforderungen.md
ue03/sraks/kontext.md
ue03/sraks/zuordnung.md
ue03/ssda78/anforderungen.md
ue03/ssda78/kontext.md
ue03/ssda78/zuordnung.md
ue03/sshj44/anforderungen.md
ue03/sshj44/kontext.md
ue03/sshj44/zuordnung.md
ue03/stmx/anforderungen.md
ue03/stmx/kontext.md
ue03/stmx/zuordnung.md
ue03/talh/anforderungen.md
ue03/talh/kontext.md
ue03/talh/zuordnung.md
ue03/tcam/anforderungen.md
ue03/tcam/kontext.md
ue03/tcam/zuordnung.md
ue03/tiger/anforderungen.md
ue03/tiger/kontext.md
ue03/tiger/zuordnung.md
ue03/tnd/anforderungen.md
ue03/tnd/kontext.md
ue03/tnd/zuordnung.md
ue03/trry/anforderungen.md
ue03/trry/kontext.md
ue03/trry/zuordnung.md
ue03/tyfncc/anforderungen.md
ue03/tyfncc/kontext.md
ue03/tyfncc/zuordnung.md
ue03/uwar/anforderungen.md
ue03/uwar/kontext.md
ue03/uwar/zuordnung.md
ue03/val/anforderungen.md
ue03/val/kontext.md
ue03/val/zuordnung.md
ue03/vic26/anforderungen.md
ue03/vic26/kontext.md
ue03/vic26/zuordnung.md
ue03/virus/anforderungen.md
ue03/virus/kontext.md
ue03/virus/zuordnung.md
ue03/wnga/anforderungen.md
ue03/wnga/kontext.md
ue03/wnga/zuordnung.md
ue03/ygue/anforderungen.md
ue03/ygue/kontext.md
ue03/ygue/zuordnung.md
ue03/ykar/anforderungen.md
ue03/ykar/kontext.md
ue03/ykar/zuordnung.md
ue03/z-266/anforderungen.md
ue03/z-266/kontext.md
ue03/z-266/zuordnung.md
ue03/zc/anforderungen.md
ue03/zc/kontext.md
ue03/zc/zuordnung.md
ue03/zcbn/anforderungen.md
ue03/zcbn/kontext.md
ue03/zcbn/zuordnung.md
ue03/zcoel/anforderungen.md
ue03/zcoel/kontext.md
ue03/zcoel/zuordnung.md
ue03/zsh/anforderungen.md
ue03/zsh/kontext.md
ue03/zsh/zuordnung.md
ue04/README.md
ue04/_vorlage/einrichtung.md


**Tool: shell**

**Input:**
```json
{
  "command": "Get-ChildItem -Directory | Select-Object Name; Write-Output \"---ue04---\"; Get-ChildItem ue04 -ErrorAction SilentlyContinue | Select-Object Name"
}
```


Name     
----     
ue01     
ue02     
ue03     
ue04     
---ue04---
_vorlage 
README.md




---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git ls-tree -r --name-only HEAD | Select-String -Pattern 'ecib'; Write-Output \"---ue04 readme---\"; Get-Content ue04/README.md; Write-Output \"---vorlage---\"; Get-Content ue04/_vorlage/einrichtung.md"
}
```


ue01/steckbriefe/ecib.md
ue03/ecib/anforderungen.md
ue03/ecib/kontext.md
ue03/ecib/zuordnung.md
---ue04 readme---
# �obung 4 �?" Einen Coding Agent einrichten

In dieser �obung installieren Sie einen Coding Agent �?" das �obungsblatt
beschreibt opencode �?", verbinden ihn mit einem Sprachmodell und setzen ihn
zum ersten Mal in Ihrem lokalen Klon dieses Repositorys ein. Die Aufgaben stehen im
[�obungsblatt](https://carstenlucke.github.io/thm_wk-1208_softwaretechnik/ue04-coding-agent/).

## Was Sie einreichen

Einzureichen ist ein Verzeichnis `ue04/<benutzername>/` mit zwei Dateien,
und zwar als Pull Request vom Branch `ue04-<benutzername>`. Gemeint ist Ihr
GitHub-Benutzername in Kleinbuchstaben.

| Datei | Aufgabe | Woher |
|---|---|---|
| `einrichtung.md` | 1 und 2 �?" womit Sie arbeiten, und ob die Antwort des Agenten stimmt | aus `_vorlage/` |
| `sitzung.md` | 2 �?" die Sitzung mit dem Agenten | entsteht mit `/export` in Ihrem Agenten |

1. Kopieren Sie das Verzeichnis `_vorlage` nach `<benutzername>`. Die Vorlage
   selbst bleibt unver��ndert.
2. FǬllen Sie `einrichtung.md` im Lauf der �obung aus und legen Sie
   `sitzung.md` hinzu. Entfernen Sie dort vor dem Commit Pfade mit dem
   Namen Ihres Kontos auf dem Rechner, Namen und E-Mail-Adressen; das
   Repository ist ��ffentlich.

L��uft Ihr Agent nicht, reichen Sie trotzdem ein: nur
`einrichtung.md`, mit *nein* oder *teilweise* bei �?zL��uft der Agent?�?o und
einem Beleg im Abschnitt �?zWenn es nicht l��uft�?o �?" Schritt, Befehl samt Ausgabe (w��rtlich)
und was Sie bereits versucht haben.

Das �obungsblatt beschreibt opencode, schreibt es aber nicht vor. Wer schon
mit einem anderen Agenten arbeitet �?" Claude Code, Codex, GitHub Copilot in
VS Code oder als Copilot CLI, eine andere Erweiterung �?", darf ihn verwenden
und tr��gt ihn in `einrichtung.md` unter �?zWerkzeug�?o ein.

Weitere Dateien, welche der Agent anlegt, geh��ren nicht in den Pull Request.

> [!IMPORTANT]
> FǬr diese �obung gibt es 1 Bonuspunkt. Diesen erh��lt nur, wer bis zur
> Frist im Moodle-Kurs selbst einen Pull Request mit Inhalten gestellt hat.
---vorlage---
# Einrichtung �?" Coding Agent

<!-- Aufgaben 1 und 2 des �obungsblatts. Ersetzen Sie jedes �?z�?݃?o durch Ihre
     Angabe; die �oberschriften bleiben stehen. L��schen Sie die Kommentare,
     sobald Sie fertig sind. Die Sitzung mit dem Agenten geh��rt nicht
     hierher, sondern als Export in die Datei sitzung.md daneben. -->

## Aufbau

| Angabe | Ihre Angabe |
|---|---|
| L��uft der Agent? | �?� |
| Werkzeug | �?� |
| Version | �?� |
| Betriebssystem | �?� |
| Modellzugang | �?� |
| Modell | �?� |

<!-- L��uft der Agent?: ja, teilweise oder nein. Teilweise hei�Yt, er
     startet, aber ein Schritt danach scheitert (Anmeldung, Antwort,
     Export). Bei teilweise und nein belegen Sie unten unter �?zWenn es nicht
     l��uft�?o, woran es scheitert; ohne laufenden Agenten entf��llt sitzung.md.
     Werkzeug: opencode, oder wer schon damit arbeitet, Claude Code, Codex,
     GitHub Copilot (in VS Code oder als Copilot CLI) oder ein anderer
     Agent. Version: Ausgabe von `opencode --version` bzw.
     die Versionsangabe Ihres Werkzeugs.
     Betriebssystem: macOS, Windows, Windows mit WSL oder Linux.
     Modellzugang: GitHub Copilot, ChatGPT, OpenCode Zen (kostenlos), Claude
     oder ein anderer. Modell: so, wie es in der Auswahl hei�Yt, in opencode
     unter /models. -->

## Antwort des Agenten geprǬft

<!-- Aufgabe 2, Schritt 8: Vergleichen Sie die Antwort des Agenten in
     sitzung.md mit dem, was Sie selbst wissen. Hat er alle Ihre Dateien
     gefunden? Hat er etwas Fremdes fǬr Ihres gehalten oder etwas erfunden?
     Zwei bis drei S��tze. -->

�?�

## Wenn es nicht l��uft

<!-- Pflicht bei �?zteilweise�?o und �?znein�?o; bei �?zja�?o l��schen Sie alles unter
     der �oberschrift. In den Kasten geh��rt der Befehl, der scheitert, samt
     seiner Ausgabe, w��rtlich aus dem Terminal kopiert. -->

**Schritt, an dem es scheitert:** �?�

**Befehl und Ausgabe:**

```text
�?�
```

**Bereits versucht:** �?�




**Tool: shell**

**Input:**
```json
{
  "command": "git log --oneline --all --author-date-order -- '*ecib*' | Select-Object -First 20; Write-Output \"---config---\"; git config user.name; git config user.email; Write-Output \"---branch upstream---\"; git log --oneline origin/ue04-ecib -5 2>$null"
}
```

86ee651 On main: Zwischenspeicherung Uebung 3
0fa0546 Uebung 3: Anforderungen an den Terminplaner (#393)
ecf1ae3 Uebung 3: Anforderungen an den Terminplaner
14299f3 Update rollen.md
2c50307 Update contributor name in rollen.md
738952b Revise specification document with detailed sections
ab3e083 Zugabe: Rollen für ecib
b5a13ea Ergebnisse der Übung 2 für ecib
2eb5ce7 Gesprächsnotiz für mmus in Form bringen
6f8d19d Steckbrief ecib (#62)
b759660 Update Steckbrief für ecib anlegen
d5f1979 Steckbrief für ecib anlegen
---config---
Erik Cibis
erik.cibis@mnd.thm.de
---branch upstream---

Exited with code 1

---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git log --all --format='%h|%an|%ae|%ad|%s' --date=short | Select-String -Pattern 'Cibis|ecib|erik' | Select-Object -First 40"
}
```


86ee651|Erik Cibis|erik.cibis@mnd.thm.de|2026-11-05|On main: Zwischenspeicherung Uebung 3
868eac8|Erik Cibis|erik.cibis@mnd.thm.de|2026-11-05|index on main: b5dbd3a Ü2: Ergebnisse von thm-nos (#400)
0fa0546|ErikCibis|erik.cibis@mnd.thm.de|2026-11-02|Uebung 3: Anforderungen an den Terminplaner (#393)
ecf1ae3|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-30|Uebung 3: Anforderungen an den Terminplaner
14299f3|ErikCibis|erik.cibis@mnd.thm.de|2026-10-26|Update rollen.md
2c50307|ErikCibis|erik.cibis@mnd.thm.de|2026-10-26|Update contributor name in rollen.md
738952b|ErikCibis|erik.cibis@mnd.thm.de|2026-10-26|Revise specification document with detailed sections
ab3e083|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-26|Zugabe: Rollen für ecib
b5a13ea|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-26|Ergebnisse der Übung 2 für ecib
2eb5ce7|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-26|Gesprächsnotiz für mmus in Form bringen
6f8d19d|ErikCibis|erik.cibis@mnd.thm.de|2026-10-20|Steckbrief ecib (#62)
b759660|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-16|Update Steckbrief für ecib anlegen
d5f1979|Erik Cibis|erik.cibis@mnd.thm.de|2026-10-16|Steckbrief für ecib anlegen




**Tool: shell**

**Input:**
```json
{
  "command": "git show --stat --oneline b5a13ea; Write-Output \"---stash---\"; git show --stat --oneline 86ee651; Write-Output \"---branch list---\"; git branch -a -vv"
}
```

b5a13ea Ergebnisse der Übung 2 für ecib
 ue02/ecib/notiz.md         | 31 ++++++++++----------
 ue02/ecib/phasenplan.md    | 70 ++++++++++++++++++++++++++++++++++++++++++++++
 ue02/ecib/spezifikation.md | 16 +++++++++++
 3 files changed, 101 insertions(+), 16 deletions(-)
---stash---
86ee651 On main: Zwischenspeicherung Uebung 3

 ue03/ecib/anforderungen.md | 22 ++++++++++------------
 ue03/ecib/kontext.md       | 26 ++++++++++++++------------
 2 files changed, 24 insertions(+), 24 deletions(-)
---branch list---
  main                           b5dbd3a [origin/main] Ü2: Ergebnisse von thm-nos (#400)
  steckbrief-ecib                b759660 [origin/steckbrief-ecib] Update Steckbrief für ecib anlegen
  ue02-ecib                      ab3e083 [origin/ue02-ecib: behind 3] Zugabe: Rollen für ecib
  ue03-ecib                      ecf1ae3 [origin/ue03-ecib] Uebung 3: Anforderungen an den Terminplaner
* ue04-ecib                      b5dbd3a Ü2: Ergebnisse von thm-nos (#400)
  remotes/origin/HEAD            -> origin/main
  remotes/origin/main            b5dbd3a Ü2: Ergebnisse von thm-nos (#400)
  remotes/origin/steckbrief-ecib b759660 Update Steckbrief für ecib anlegen
  remotes/origin/ue02-ecib       14299f3 Update rollen.md
  remotes/origin/ue03-ecib       ecf1ae3 Uebung 3: Anforderungen an den Terminplaner


---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "Write-Output \"--- ue02-ecib tree ---\"; git ls-tree -r --name-only ue02-ecib | Select-String -Pattern 'ue02/ecib'; Write-Output \"--- ue03-ecib tree ---\"; git ls-tree -r --name-only ue03-ecib | Select-String -Pattern 'ue03/ecib'; Write-Output \"--- ue03 on main vs branch diff ---\"; git diff --stat main..ue03-ecib -- ue03/ecib; Write-Output \"--- stash files ---\"; git stash list"
}
```

--- ue02-ecib tree ---

ue02/ecib/notiz.md
ue02/ecib/phasenplan.md
ue02/ecib/rollen.md
ue02/ecib/spezifikation.md
--- ue03-ecib tree ---
ue03/ecib/anforderungen.md
ue03/ecib/kontext.md
ue03/ecib/zuordnung.md
--- ue03 on main vs branch diff ---
--- stash files ---
stash@{0}: On main: Zwischenspeicherung Uebung 3
stash@{1}: On ue02-ecib: Zwischenspeicherung Uebung 2




**Tool: read**

**Input:**
```json
{
  "path": "D:\\Git\\thm_wk-1208_softwaretechnik-uebungen\\ue01\\steckbriefe\\ecib.md"
}
```

Read file D:\Git\thm_wk-1208_softwaretechnik-uebungen\ue01\steckbriefe\ecib.md, lines 1-14
1: # Steckbrief ecib
2: 
3: ## Studiengang und Semester
4: 
5: Organisations & IT-Sicherheit
6: 
7: ## Meine bisherige Erfahrung mit Softwareentwicklung
8: 
9: Grundkenntnisse Java durch IT-Fachabi und 1/2 Semester.
10: Grundkenntnisse Webentwicklung (HTML, CSS, JS, PHP)
11: 
12: ## Das erwarte ich von der Veranstaltung
13: 
14: Ich möchte merh Technisches verständnis mir an eignen.

**Tool: read**

**Input:**
```json
{
  "path": "D:\\Git\\thm_wk-1208_softwaretechnik-uebungen\\ue03\\ecib\\zuordnung.md"
}
```

Read file D:\Git\thm_wk-1208_softwaretechnik-uebungen\ue03\ecib\zuordnung.md, lines 1-37
1: # Anforderung oder Lösung? — Terminplaner für die THM
2: 
3: Kürzel: ecib
4: 
5: ## Funktionale Anforderung (FA)
6: 
7: - Studierende können einen freien Sprechstundentermin bei einer Lehrperson buchen.
8: - Die Anmeldung erfolgt ausschließlich über das Hochschulkonto.
9: - Vor jeder Buchung fragt die Komponente „Buchung“ bei der Komponente „Kalender“ an, ob der Termin noch frei ist.
10: - Die API nimmt Anfragen als REST-Aufrufe entgegen und antwortet in JSON.
11: - Jeder gebuchte Termin lässt sich als iCal-Datei herunterladen.
12: - Die Buchungsseite ist mit einem Screenreader vollständig bedienbar.
13: - Das System wird im Rechenzentrum der THM betrieben.
14: - Über die API kann ein KI-Agent freie Termine abfragen und im Namen einer Person buchen.
15: 
16: ## Qualitätsanforderung (QA)
17: 
18: - Termine werden in einer PostgreSQL-Datenbank gespeichert.
19: - Sagt eine Lehrperson eine Sprechstunde ab, erhalten alle, die gebucht haben, eine Nachricht.
20: - Personenbezogene Daten werden nach den Vorgaben der EU-DSGVO verarbeitet.
21: - Auch zu Beginn der Prüfungsanmeldung, wenn bis zu 2.000 Personen zugleich buchen, zeigt das System eine Seite in weniger als zwei Sekunden an.
22: 
23: ## Randbedingung (RB)
24: 
25: - Ein bereits gebuchter Termin kann kein zweites Mal gebucht werden.
26: - Ein Sekretariat sieht alle Prüfungstermine seines Fachbereichs auf einen Blick.
27: 
28: ## Keine Anforderung — Lösung (WIE)
29: 
30: - Eine Buchung ist für Studierende in höchstens drei Schritten abgeschlossen.
31: - Die erste Ausbaustufe geht zum Sommersemester 2027 in Betrieb.
32: 
33: ## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?
34: 
35: Keine Karte markiert.
36: 
37: <!-- zuordnung ue03-anforderung-oder-loesung: k01=fa k02=qa k03=fa k04=wie k05=rb k06=wie k07=fa k08=qa k09=qa k10=qa k11=fa k12=fa k13=fa k14=rb k15=fa k16=fa | unsicher: – -->

---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "foreach ($f in @('ue02/ecib/notiz.md','ue02/ecib/phasenplan.md','ue02/ecib/spezifikation.md','ue02/ecib/rollen.md','ue03/ecib/anforderungen.md','ue03/ecib/kontext.md')) { Write-Output \"=== $f ===\"; git show \"ue02-ecib:$f\" 2>$null | Select-Object -First 12 }"
}
```

=== ue02/ecib/notiz.md ===
<!-- Diese Notiz hat noch keine Form. Bringen Sie sie in Markdown, wie es
     Aufgabe 1 des Übungsblatts beschreibt, ohne am Inhalt etwas zu ändern.
     Löschen Sie diesen Kommentar, sobald Sie fertig sind. -->

# Gesprächsnotiz: Terminplaner für die THM
## Worum es geht
Die THM möchte eine Software zur Planung und Vereinbarung von Terminen. Lehrende bieten Sprechstunden und Prüfungstermine an, Studierende buchen sie, Sekretariate behalten den Überblick.
Die Software soll sich über das Hochschulkonto bedienen lassen. Zunächst soll sie Termine als iCal-Datei zum Herunterladen anbieten, später vielleicht direkt in die Kalender der Beteiligten eintragen.
Außerdem soll sie eine API bekommen, über die KI-Agenten sie steuern können.
Die THM sagte dazu wörtlich: Wir wollen nicht noch ein Werkzeug, das am Ende keiner benutzt.
Wichtig: Noch ist nichts beauftragt, wir sollen zuerst einen Vorschlag machen.
## Was heute benutzt wird
=== ue02/ecib/phasenplan.md ===
# Phasenplan — Terminplaner für die THM

Kürzel: ecib

## Studie

**Ergebnis der Phase:** …

- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt

## Systemspezifikation

=== ue02/ecib/spezifikation.md ===
# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @…

<!-- Je Abschnitt Ihrer Gliederung eine Überschrift (## für Abschnitte, ###
     für Unterabschnitte) und darunter ein Beispiel aus dem Terminplaner,
     d.h. so, wie Sie den Sachverhalt in diesem Abschnitt festhalten würden.
     Die beiden Überschriften unten sind lediglich Platzhalter. -->

## …

…
=== ue02/ecib/rollen.md ===
# Rollen — Terminplaner für die THM

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @…

## Der Kunde

| Bereich | Wer ist das an der THM? | Woran machen Sie es fest? |
|---|---|---|
| Fachbereich (eigentlicher Auftraggeber) | … | … |
| IT-Bereich | … | … |

## Das Projektteam
=== ue03/ecib/anforderungen.md ===
=== ue03/ecib/kontext.md ===

Exited with code 1

---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "foreach ($f in @('ue03/ecib/anforderungen.md','ue03/ecib/kontext.md')) { Write-Output \"=== $f ===\"; Get-Content $f | Select-Object -First 10 }"
}
```

=== ue03/ecib/anforderungen.md ===
# Anforderungen �?" Terminplaner fǬr die THM

<!-- Aufgabe 3 des �obungsblatts, ohne Hilfsmittel. Je Zeile eine
     Anforderung in einem Satz, dazu der Stakeholder, von dem sie stammt,
     und die Art: FA, QA oder RB. Mindestens acht Anforderungen, davon
     mindestens zwei je Art; die Nummern laufen A01, A02 �?� L��schen Sie die
     Kommentare, sobald Sie fertig sind. -->

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
=== ue03/ecib/kontext.md ===
# Stakeholder und Systemkontext �?" Terminplaner fǬr die THM

<!-- Aufgabe 1 des �obungsblatts. Ersetzen Sie die Platzhalter �?� und fǬgen
     Sie so viele Zeilen hinzu, wie Sie ben��tigen. L��schen Sie die
     Kommentare, sobald Sie fertig sind. -->

## Stakeholder

<!-- Mindestens sechs Stakeholder, je mit einem Satz dazu, worauf sie
     Einfluss haben. -->


---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git branch --contains b5a13ea; Write-Output \"---\"; git branch --contains 6f8d19d; Write-Output \"---status---\"; git status --short --branch"
}
```

  ue02-ecib
---
  main
  ue02-ecib
  ue03-ecib
* ue04-ecib
---status---
## ue04-ecib


---

## Assistant

**Tool: shell**

**Input:**
```json
{
  "command": "git log --oneline ue02-ecib..origin/ue02-ecib; Write-Output \"---files remote---\"; git ls-tree -r --name-only origin/ue02-ecib | Select-String -Pattern 'ue02/ecib'"
}
```

14299f3 Update rollen.md
2c50307 Update contributor name in rollen.md
738952b Revise specification document with detailed sections
---files remote---

ue02/ecib/notiz.md
ue02/ecib/phasenplan.md
ue02/ecib/rollen.md
ue02/ecib/spezifikation.md




---

## Assistant

## Was im Repository liegt

Das ist das Übungsrepository zur Veranstaltung **Softwaretechnik** (THM). Es hat vier Übungsverzeichnisse, jeweils mit eigener `README.md`, Vorlagen (`_vorlage/`, teils `_zugabe/`) und den Abgaben der Studierenden:

| Verzeichnis | Inhalt |
|---|---|
| `ue01/` | Steckbriefe unter `ue01/steckbriefe/<benutzername>.md` |
| `ue02/` | Je Person `notiz.md`, `phasenplan.md`, `spezifikation.md` (teils `rollen.md`) |
| `ue03/` | Je Person `anforderungen.md`, `kontext.md`, `zuordnung.md` |
| `ue04/` | Bisher nur `README.md` und `_vorlage/einrichtung.md` |

Dazu kommen `README.md` und `AGENTS.md` im Wurzelverzeichnis. Der aktuelle Branch ist `ue04-ecib`, er steht auf dem Stand von `main`, und der Arbeitsbaum ist sauber. Ein `ue04/ecib/` gibt es noch nicht.

## Deine Dateien

Deine Kennung ist **`ecib`** (so heißt der Branch und so hießen deine bisherigen Abgaben). Von dir stammen:

- `ue01/steckbriefe/ecib.md`
- `ue03/ecib/anforderungen.md`
- `ue03/ecib/kontext.md`
- `ue03/ecib/zuordnung.md`

Diese drei `ue03`-Dateien liegen auch auf `main`. Für Übung 2 gibt es zusätzlich:

- `ue02/ecib/notiz.md`
- `ue02/ecib/phasenplan.md`
- `ue02/ecib/spezifikation.md`
- `ue02/ecib/rollen.md` (Zugabe)

**Achtung:** `ue02/ecib/` ist **nicht** in `main` enthalten, sondern nur im Branch `ue02-ecib`. Der lokale Branch hinkt gegenüber `origin/ue02-ecib` um drei Commits hinterher (u. a. „Update rollen.md“).

Außerdem liegen zwei Zwischenstände als **Stash** herum, also nicht in einem Branch gesichert:

- `stash@{0}`: „Zwischenspeicherung Übung 3“ (`ue03/ecib/anforderungen.md`, `kontext.md`)
- `stash@{1}`: „Zwischenspeicherung Übung 2“

Alle anderen Dateien – insbesondere die `README.md`-Dateien, `_vorlage/`, `_zugabe/` und die Verzeichnisse anderer Personen – gehören nicht dir. Für Übung 4 fehlen dir noch `ue04/ecib/einrichtung.md` und `ue04/ecib/sitzung.md`.

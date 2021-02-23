# Unit_Testing_and_Logging

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Soley02/Unit_Testing_and_Logging/HEAD)

Ein Binder-Kompatibles Repository mit einer `requirements.txt` und `runtime.txt` Datei.

Sie können auch unter der folgenden Binder-URL dieses Notebook erzeugen:

https://mybinder.org/v2/gh/Soley02/Unit_Testing_and_Logging/HEAD

## Ausführung:

Für die Auführung durch MyBinder, wurden die hier enthalten Dateien verwendet. 

Die Daten welches in den ML-Beispielen verwendet wurden, sind ebenfalls direkt abrufbar im Code und müssen nicht zusätzlich heruntergeladen werden.

1. Schritt: Auf Badge von MyBinder klicken oder per LINK
2. Schritt: Warten bis alle erforderlichen Pakete/Module durch MyBinder hinzugefügt sind
3. Schritt: MyBinder wurde erfolgreich durchgeführt und Jyupter Notebook (Nbviewer) öffnet sich
4. Schritt: Der Code kann komplett ausgeführt werden 

### Notes

Die `requirements.txt` Datei listet alle Python-Bibliotheken auf, die für dieses Notebook erforderlich sind. Diese werden automatisch installiert:

```
pip install -r requirements.txt
```
Ausgabe im LogFile:

MNIST: (70000, 784) (70000,)
__init__ ran in: 5.245208740234375e-06 sec
fit ran in: 17.269278049468994 sec

Train Accuracy: 72.92166666666667 

Train confusion matrix:
5447    5   40   31   49   16  198   50   81    6
   3 6440  127   54    3   29   25   36   24    1 
 297  420 3824  163  256   19  622  186  121   50
 124  221  255 4566   54  251   97  129  275  159
 104  128   26   54 4546  342  206  133   96  207
 399  200  109 1081  416 2227  289  363  228  109
 173   89  112   55  156  229 5034   25   45    0
 213  192  205   39  160   17   26 5058   60  295
  67  690  202  677   73  188  347   39 3437  131
 164  162   63  290  669  279  122  735  291 3174

Classification report for classifier:
              precision    recall  f1-score   support

        0.0       0.79      0.94      0.86       980
        1.0       0.77      0.96      0.85      1135
        2.0       0.78      0.65      0.71      1032
        3.0       0.66      0.76      0.71      1010
        4.0       0.70      0.76      0.73       982
        5.0       0.62      0.41      0.49       892
        6.0       0.69      0.83      0.76       958
        7.0       0.76      0.80      0.78      1028
        8.0       0.74      0.61      0.67       974
        9.0       0.78      0.56      0.65      1009

avg / total       0.73      0.73      0.73     10000


predict ran in: 0.04868912696838379 sec

Test Accuracy: 73.4 

Test confusion matrix:
 923    1    2    3    3    1   35    3    9    0
   0 1084   23   11    0    0    5    4    8    0
  63   78  669   27   38    2   97   28   24    6
  20   27   35  770    8   42   18   27   45   18
  15   21    3    8  750   60   45   23   18   39
  56   24   15  193   73  362   56   58   38   17
  35   10   18   11   28   42  799    6    8    1
  23   40   52    6   21    4    7  821    8   46
  14   90   29   99   10   33   66    7  598   28
  21   27   10   37  133   42   27  100   48  564

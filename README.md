![Screenshot commit 1.2](commit-1-2.png)
Dari screenshot di atas, dapat dilihat bahwa output dari program tersebut secara berurutan adalah "hey hey" dan diikuti oleh "howdy!" "done!". Hal ini disebabkan "hey hey" berada di luar fungsi async yang mana akan terus melanjutkan program hingga selesai sambil menunggu hasil dari future yaitu dalam konteks ini mencetak "howdy!" dan "done!".

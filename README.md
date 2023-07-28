

```
r language BS3, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis makroveziküler ve mikroveziküler steatoz, lipogranülom, karaciğer , echo = (language == "TR")
## BS3 - makroveziküler ve mikroveziküler steatoz, lipogranülom, karaciğer {#sec-BS3 }
```


```
asis macrovesicular and microvesicular steatosis, lipogranuloma, liver , echo = (language == "EN")
## BS3 - macrovesicular and microvesicular steatosis, lipogranuloma, liver {#sec-BS3 }
```






```
r BS3 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS3-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS3/HE.html",
  file = "./screenshots/BS3-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**makroveziküler ve mikroveziküler steatoz, lipogranülom, karaciğer**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS3-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS3/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS3/HE.html)
```

```
asis, echo = (language == "EN")

**macrovesicular and microvesicular steatosis, lipogranuloma, liver**

[![Click for Full Screen WSI](./screenshots/BS3-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS3/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS3/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS3/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS3/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

makroveziküler ve mikroveziküler steatoz, lipogranülom, karaciğer

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

macrovesicular and microvesicular steatosis, lipogranuloma, liver

:::

```









:::::

<hr>

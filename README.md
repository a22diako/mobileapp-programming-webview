
# Rapport inl2

Jag har genom external och internal links kunnat koppla min app till hemsidor samt en html fil.
Internal linken pekar på en html fil som jag gjort. I denna html filen har jag lagt en h1 för att man ska se att den är länken är rätt kopplad.

Hänvisar till kod nedanför.

    ```
    public void showExternalWebPage(){
    myWebView.loadUrl("https://www.youtube.com/");
    }

    public void showInternalWebPage(){
    myWebView.loadUrl("file:///android_asset/inl2.html");
    }
    ```

Som även är kopplad till:

```
if (id == R.id.action_external_web) {
showExternalWebPage();
Log.d("==>","Will display external web page");
return true;
}

    if (id == R.id.action_internal_web) {
    showInternalWebPage();
    Log.d("==>","Will display internal web page");
    return true;
    }
```

![](htmlscreen.didi.png)




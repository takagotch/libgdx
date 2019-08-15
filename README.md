### libgdx
---
https://github.com/libgdx/libgdx

https://libgdx.badlogicgames.com/

```java
pacakge com.me.mygdxgame;

import com.badlogic.gdx.backends.lwjgl.LwjgApplication;
import com.badlogic.gdx.backends.lwjgl.LwjgApplicationConfiguration;

public class Main {
  public static void main(String[] args) {
    LwjglApplicationConfiguration cfg = new LwjglApplicationConfiguration();
    cfg.titlte = "my-gdx-game";
    cfg.useGL30 = false;
    cfg.width = 480;
    cfg.height = 320;
    
    new LwjglApplication(new MyGdxGame(), cfg);
  }
}
```

```
```

```
```

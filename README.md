# MultiLanguages
语言国际化，不需要任何代码，只要简历对应语言的values—strings文件夹以及文件即可

上面已经讲的很清楚，不需要任何代码，只要简历对应语言的values—strings文件夹以及文件即可  然后去更改手机自身的系统语言，APP就可以自动跟随更换语言
网上有一些国际化的例子，但是都没有明说 可能会对一些初学者造成误导，所以在这里特意说一下

我的代码里面啥也没有

只有一个类就是MainActivitylk.class  如下



package com.rock.han.morelanguagestudy;

import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;
import android.widget.Toast;

import butterknife.BindView;
import butterknife.ButterKnife;
import butterknife.OnClick;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        ButterKnife.bind(this);

        //语言国际化不需要任何代码，只需要在res文件夹下面 建立对应不同语言的values文件以及下一级目录的strings文件即可
    }


}

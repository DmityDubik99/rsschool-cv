# **Resume**
**First Name** _Dmitry_
**Last Name** _Dubovicky_
### Contact Info
**telephone** +375291446368
**e-mail** duboviczkij_dmitrij@mail.ru


_I want to become a professional android developer so the quality of knowledge is very important for me_
_.I am studying at Belarusian-Russian University. I studied c#, JS, Java, and databases._
### Code examples 
    package com.example.my2;

    import androidx.appcompat.app.AppCompatActivity;

    import android.content.Intent;
    import android.os.Bundle;
    import android.view.Menu;
    import android.view.MenuItem;

    public class Activitu1 extends AppCompatActivity {

        @Override
        public boolean onCreateOptionsMenu(Menu menu) {
            menu.add(0,0,0,"Вернуться");
            menu.add(0,1,1,"Выйти");
            return super.onCreateOptionsMenu(menu);
        }
        @Override
        public boolean onOptionsItemSelected(MenuItem item) {
            if (item.getItemId() == 0) {
                Intent intent = new Intent(this, MainActivity.class);
                startActivity(intent);
            } else if (item.getItemId() == 1) {
                finish();
            }
            return super.onOptionsItemSelected(item);
        }

        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_activitu1);
        }
    }

**Experience**  😪

**Education** _A 4th-year student in the field of software engineering._

_Approximate level of English A2, I am study independently._
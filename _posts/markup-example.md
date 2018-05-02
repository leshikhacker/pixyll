---
layout:     post
title:      Markup example
date:       2017-11-03 09:30:00
summary:    Не субота шоста ранку, але доволі рано прокинувся, хоча поспав лише годину. Певно, це можна назвати сном..
categories: road
---

Не субота шоста ранку, але доволі рано прокинувся, хоча поспав лише годину. Певно, це можна назвати сном, коли слухаєш храп сусіда у хостелі, не витримуєш й починаєш блукати ранішнім містом провітрити думки. Сьогодні це Таллінн, власне тут пару днів, але не суть. Просто для атмосфери, певно кожен має (або не має) свої асоціації із цим містом, для мене - це в першу чергу стріт-арт й, по класиці, вузенькі вулички.

Думки, здається їх багато, але водночас так мало. Треба сформувати пару тез: <ins>плани</ins>, <ins>подорожі</ins>, <ins>автостоп</ins>, <ins>кауч</ins>, <ins>квапитися або ні</ins>, <ins>спілкування із людьми</ins>, <ins>сенс</ins>, <ins>уповільнити час й отримати насолоду</ins>.

Здавалось б, гуляю ранішнім містом, з іншого боку усі нормальні супермаркети зачинені й ніде не можу купити рисового молока, а воно тут дуже смачне, тому рекомендую. Повертаюся на диван кухні, на фоні якісь люди, чомусь маю вдачу обирати місця, хостел був ніби створений для всіх прибульців із СНД. Плани як завше не здійснюються, або запізнілі, як і моя мандрівка. Прибалтика холодна, пам’ятаю “як вчора”, намагався у дощову погоду доїхати із Вільнюса до Риги, автостопом, по хардкору. Наступного дня взяв квиток на автобус й із комфортом. Це я очевидні речі, що краще не робити цього вночі, а тим паче під дощ, також залишати більше часу на вивчення нового місця, аби якомога більше відчути його красу й прожити дні в унісон із навколишнім осередком. Але ж план-план, як людина, яка ходить на своїх двох, для швидких пересувань на великі відстані, залежу від інших.

Втім плани великі, а мене не стає, тому на ходу змінюю, корегую, аби отримати максимум задоволення. Один-два дні на країну/місто дуже замало, потрібен час на відновлення сил й енергії, не тільки фізичних. Власне так, майже безсенсовно пройшли мої дні у Ризі, у порівнянні із великим й захоплюючим старим Вільнюсом, вона здалася майже нічим не цікавою комашкою. Але варто збирати враження, просто як у житті, справа не у кількості, а якості. Коли місто не зачаровує, то це роблять люди й гаряче смачне какао.

Кауч працює, як у ЄС, так у Білорусі, хоча із Литвою-Латвією не дуже пощастило, шукаю в останні дні. Вчора мав їхати до Пітера, але вирішив почекати до завтра, так би не було б цього ранку, цих слів, але мало місце бути чомусь іншому, “нічого” - це також щось, але розчинене у вакуумі думок й заховане у корках підсвідомості.

А із людьми по-різному, з деякими розмовляєте про все й одразу, після години такого “інтенсиву” сідають геть усі батарейки, а з іншими помаленьку, але також приємно. Тут балансу немає, єдине що, мовчання час від часу сіє ніяковість, яка вбиває. До нескінченності, є “свої” й не “свої” люди, правильний чи не дуже час.

А там де люди й тіндер. Хоча іноді стають сумніви, що там справді люди, коли передивишся й просвайпаєш 100500 фото. Я не соціофоб чи гірше, а справа в тому, що кожен намагається на фото показати себе із кращого боку, не тим, ким є у житті. Мав доволі кумедні випадки, коли страшенно лякався, випадково побачивши героїнь віртуальної переписки у реальному житті. Брало сумління, звичайно, людина - це особистість, а не зовнішність, але хто винен в тому, що перше враження не зіграєш. Якось так гуляв із дівчиною, вищою мене на дві, а то й три голови, ніяковості уникнути не вдалося. Тож свайпай, але очікуй на будь-які несподіванки. 

Життя дивує й взагалі люди дивні створіння. Наостанок відсиплю трохи свтлин із ранішньої прогулянки. Усім смачного ранку, нехай вихідні не обтяжуються буднями, а будні вирують яскравими кольорами!

PS. Хто не зрозумів, на початку статті відсилка була на пісню <ins>Animall Jazz</ins> “Суббота 6 утра”.


{% highlight ruby lineanchors %}
# The most awesome of classes
class Awesome < ActiveRecord::Base
  include EvenMoreAwesome

  validates_presence_of :something
  validates :email, email_format: true

  def initialize(email, name = nil)
    self.email = email
    self.name = name
    self.favorite_number = 12
    puts 'created awesomeness'
  end

  def email_format
    email =~ /\S+@\S+\.\S+/
  end
end
{% endhighlight %}

Here's some CSS:

{% highlight css %}
.foobar {
  /* Named colors rule */
  color: tomato;
}
{% endhighlight %}

Here's some JavaScript:

{% highlight js %}
var isPresent = require('is-present')

module.exports = function doStuff(things) {
  if (isPresent(things)) {
    doOtherStuff(things)
  }
}
{% endhighlight %}

Here's some HTML:

{% highlight html %}
<div class="m0 p0 bg-blue white">
  <h3 class="h1">Hello, world!</h3>
</div>
{% endhighlight %}

# Headings!

They're responsive, and well-proportioned (in `padding`, `line-height`, `margin`, and `font-size`).
They also heavily rely on the awesome utility, [BASSCSS](http://www.basscss.com/).

##### They draw the perfect amount of attention

This allows your content to have the proper informational and contextual hierarchy. Yay.

### There are lists, too

  * Apples
  * Oranges
  * Potatoes
  * Milk

  1. Mow the lawn
  2. Feed the dog
  3. Dance

### Images look great, too

![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)

_![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)_


### There are also pretty colors

Also the result of [BASSCSS](http://www.basscss.com/), you can <span class="bg-dark-gray white">highlight</span> certain components
of a <span class="red">post</span> <span class="mid-gray">with</span> <span class="green">CSS</span> <span class="orange">classes</span>.

I don't recommend using blue, though. It looks like a <span class="blue">link</span>.

### Footnotes!

Markdown footnotes are supported, and they look great! Simply put e.g. `[^1]` where you want the footnote to appear,[^1] and then add
the reference at the end of your markdown.

### Stylish blockquotes included

You can use the markdown quote syntax, `>` for simple quotes.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse quis porta mauris.

However, you need to inject html if you'd like a citation footer. I will be working on a way to
hopefully sidestep this inconvenience.

<blockquote>
  <p>
    Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.
  </p>
  <footer><cite title="Antoine de Saint-Exupéry">Antoine de Saint-Exupéry</cite></footer>
</blockquote>

### There's more being added all the time

Checkout the [Github repository](https://github.com/johnotander/pixyll) to request,
or add, features.

Happy writing.

---

[^1]: Important information that may distract from the main text can go in footnotes.

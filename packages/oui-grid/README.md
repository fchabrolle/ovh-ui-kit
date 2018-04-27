# oui-grid

<component-status cx-design="partial" ux="beta"></component-status>

## Installation

```less
  @import 'oui-grid/grid';
```

## Grid system

### Grid system 4 columns

```html:preview
<div class="oui-grid oui-grid-4">
  <div><div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
  <div><div class="oui-box" style="height:100%">Beatae nisi sunt consequatur voluptas maxime maiores tempora et magni modi libero? Quis amet sequi distinctio beatae tempore ipsam dicta porro, maxime iste reiciendis. Vel ducimus animi quis quasi temporibus.</div></div>
  <div><div class="oui-box" style="height:100%">Accusamus vitae dolorem reiciendis error repellendus sit facere nemo placeat corporis dicta. Corporis esse sapiente repellat magnam? Quam ex provident consectetur perspiciatis corrupti suscipit odio vitae, numquam et perferendis quidem!</div></div>
  <div><div class="oui-box" style="height:100%">Placeat culpa porro, voluptatum quaerat voluptates magni facere sapiente inventore dolores architecto quo fugit! Officia doloribus vel, autem, debitis dolorem provident laboriosam corporis magnam numquam molestias soluta ratione quisquam culpa.</div></div>
  <div><div class="oui-box" style="height:100%">Deleniti, provident modi quibusdam explicabo laudantium rem nostrum esse quod pariatur! Tenetur, at corporis veniam ut quae facilis deserunt id explicabo quasi, odit natus non dicta, dolorem est dignissimos esse?</div></div>
  <div><div class="oui-box" style="height:100%">Similique eius fuga esse ratione nobis non laudantium blanditiis dolorem? Fugiat voluptatibus ut ipsam asperiores corrupti? Totam laudantium excepturi, consectetur, quis eum nesciunt incidunt odit minima explicabo fugiat quia ab!</div></div>
  <div><div class="oui-box" style="height:100%">Officia neque minima eum aliquid ex, accusamus libero sapiente? Modi pariatur earum repudiandae reiciendis mollitia magnam alias ad deserunt maxime eligendi, totam nihil obcaecati enim eaque veniam! Cupiditate, iure cum?</div></div>
</div>
```

### Grid system 3 columns

```html:preview
<div class="oui-grid oui-grid-3">
  <div><div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
  <div><div class="oui-box" style="height:100%">Beatae nisi sunt consequatur voluptas maxime maiores tempora et magni modi libero? Quis amet sequi distinctio beatae tempore ipsam dicta porro, maxime iste reiciendis. Vel ducimus animi quis quasi temporibus.</div></div>
  <div><div class="oui-box" style="height:100%">Accusamus vitae dolorem reiciendis error repellendus sit facere nemo placeat corporis dicta. Corporis esse sapiente repellat magnam? Quam ex provident consectetur perspiciatis corrupti suscipit odio vitae, numquam et perferendis quidem!</div></div>
  <div><div class="oui-box" style="height:100%">Placeat culpa porro, voluptatum quaerat voluptates magni facere sapiente inventore dolores architecto quo fugit! Officia doloribus vel, autem, debitis dolorem provident laboriosam corporis magnam numquam molestias soluta ratione quisquam culpa.</div></div>
  <div><div class="oui-box" style="height:100%">Deleniti, provident modi quibusdam explicabo laudantium rem nostrum esse quod pariatur! Tenetur, at corporis veniam ut quae facilis deserunt id explicabo quasi, odit natus non dicta, dolorem est dignissimos esse?</div></div>
  <div><div class="oui-box" style="height:100%">Similique eius fuga esse ratione nobis non laudantium blanditiis dolorem? Fugiat voluptatibus ut ipsam asperiores corrupti? Totam laudantium excepturi, consectetur, quis eum nesciunt incidunt odit minima explicabo fugiat quia ab!</div></div>
  <div><div class="oui-box" style="height:100%">Officia neque minima eum aliquid ex, accusamus libero sapiente? Modi pariatur earum repudiandae reiciendis mollitia magnam alias ad deserunt maxime eligendi, totam nihil obcaecati enim eaque veniam! Cupiditate, iure cum?</div></div>
</div>
```

### Column Grid
```html:preview
<div class="oui-grid oui-grid-row">
  <div class="oui-grid-col-9">
    <div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
  </div>
  <div class="oui-grid-col-3">
    <div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
  </div>
</div>
<div class="oui-grid oui-grid-row">
    <div class="oui-grid-col-4">
      <div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
    </div>
    <div class="oui-grid-col-8">
      <div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
    </div>
  </div>
```

### Nested Grid
```html:preview
<div class="oui-grid oui-grid-row">
  <div class="oui-grid-col-9">
    <div class="oui-grid oui-grid-3">
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
      <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
    </div>
  </div>
  <div class="oui-grid-col-3">
    <div class="oui-box" style="height:100%">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
  </div>
</div>
```

## Nested Column Grid
```html:preview
<div class="oui-grid oui-grid-row">
  <div class="oui-grid-col-3">
    <div class="oui-box" style="height:100%">
      <p><strong>Column 3</strong></p>
      <div>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div>
    </div>
  </div>
  <div class="oui-grid-col-9">
    <div class="oui-grid oui-grid-row">
      <div class="oui-grid-col-8">
        <div class="oui-grid oui-grid-2">
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
          <div><div class="oui-box">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</div></div>
        </div>
      </div>
      <div class="oui-grid-col-4">
        <div class="oui-box" style="height:100%">
          <p><strong>Column 4 in column 9</strong></p>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus commodi voluptatibus numquam quaerat sit! Aspernatur facilis labore pariatur! Corrupti et eveniet, eum ex modi mollitia necessitatibus est provident error! Consequatur.</p>
        </div>
      </div>
    </div>
  </div>
</div>
```

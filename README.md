# task-01
IT修真院 css task-01

## HTML结构
```
<div class="grid-wrapper clearfix">
    <div class="grid-item">
        <div class="content"><span class="text">1</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">2</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">3</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">4</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">5</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">6</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">7</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">8</span></div>
    </div>
    <div class="grid-item">
        <div class="content"><span class="text">9</span></div>
    </div>
</div>
```

## CSS样式
```
.grid-wrapper {
    max-width: 500px;
    margin: 0 auto;
    border: 1px solid #ccc;
    padding: 3px;
}

.grid-item {
    width: calc(100% / 3);
    position: relative;
    float: left;
    padding-top: calc((100% / 3) / 2);
    padding-bottom: calc((100% / 3) / 2);

}

.grid-item .content{
    width: calc(100% - 6px);
    height: calc(100% - 6px);
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 4%;
    background-color: #e8830d;
}
.grid-item .content .text{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 20px;
}
```

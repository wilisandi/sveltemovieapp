<style>
    .box{
        background-color: chartreuse;
        text-align: center;
        padding: 15px;
        border-radius: 15px;
    }.bix{
        font-size: 20px;
    }
</style>
<div class='box'>
    <slot name='header'></slot>
    <slot name='body'>
        <span>no idea</span>
    </slot>
    <slot name='footer'></slot>
</div>
<div class='bix'>
    <p>Ini adalah teks lak an</p>
</div>
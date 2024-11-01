<script>

</script>

<div class="modal">
    <div class="modal-bg">
            <ul class="menu-list">
                <li class="current-page">
                  <a href="#home">HOME</a>
                </li>
                <li>
                  <a href="#services">SERVICES</a>
                </li>
                <li>
                  <a href="#about">ABOUT</a>
                </li>
                <li>
                  <a href="#contact">CONTACT</a>
                </li>
              </ul>
    </div>
</div>

<style>
   
    @media only screen and (max-width: 700px) {
    .active{
        visibility: hidden;
    }
    .modal{
        visibility: visible;
        width: 100%;
        position: relative;
        background-color: pink;
    }
    .modal-bg{
        background-color: white;
        margin: 0;
        position: absolute;
        top: 0;
        right: 0;
        min-width: 390px;
        text-align: center;
        
    }
    ul.menu-list{
        display: block;
        justify-content: center;
        align-content: start;
        list-style-type: none;
        padding: 0;
        margin: 0;
    }
    ul li{
        padding: 8px 0;
    }
    ul li:hover{
        background-color: #a8d0e7aa;
    }
    li a{
        text-decoration: none;
        color: black;
        padding: 10px 0;
    }
}
</style>
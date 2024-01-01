# memo--media-001
@media screen and (min-width: 768px){}

# x-t9での@mediaの切り方


selector a.vk_button_link.btn.has-background.has-vk-color-primary-background-color.btn-md {
    display: block;
    width: 50%;
    margin: 0 auto;
}
@media screen and (max-width:768px){
selector a.vk_button_link.btn.has-background.has-vk-color-primary-background-color.btn-md {
    display: block;
    width: 100%;
    margin: 0 auto;
}
}

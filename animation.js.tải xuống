var napm = document.querySelector(".lx__nap")
var napd = document.querySelector(".lx__container--nap")
var opened = document.querySelector(".lx__container--open")
var lx_ctn = document.querySelector(".lx__container")
var lx_write = document.querySelector(".lx_write")
var lx_form = document.querySelector(".lx_form")

opened.addEventListener('click', () => {
    opened.style.display = "none";
    napd.style.height = "0px";
    setTimeout(() => {
        napm.style.height = "60px";
    }, 500);
    setTimeout(() => {
        lx_write.style.transform = "translateY(-400px)"
        lx_write.style.height = "400px";
    }, 1000);
    setTimeout(() => {
        lx_write.style.transform = "translateY(-1000px)"
    }, 1500);
    setTimeout(() => {
        lx_write.style.transform = "translateY(0px)"
        lx_write.style.height = "630px"
        lx_write.style.margin = "70px 0 0 5%"
        lx_write.classList.add('br12px')
        lx_form.style.display = "flex"
    }, 2000)
})
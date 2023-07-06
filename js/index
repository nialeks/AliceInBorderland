//плавная прокрутка
const anchors = document.querySelectorAll('a[href*="#"]') //поиск всех элементов начинающихся на a href=#
for (let anchor of anchors) {
    anchor.addEventListener('click', function (e) {
        e.preventDefault() //отмена обычной работы перехода
        const id = anchor.getAttribute('href');
        document.querySelector('' + id).scrollIntoView({
            behavior: 'smooth',
            block: 'start'
        })
    })
}
//section plot
let arisu = document.getElementById('Arisu')
arisu.onmouseover = function(){
    const forphoto = document.querySelector('#forphoto')
    const img = document.createElement('img')
    img.src = 'img/arisu1.jpeg'
    img.className = 'photo_plot'
    forphoto.appendChild(img)
}
arisu.onmouseout = function(){
    document.querySelector('.photo_plot').remove()
}
let karube = document.getElementById('Karube')
karube.onmouseover = function(){
    const forphoto = document.querySelector('#forphoto')
    const img = document.createElement('img')
    img.src = 'img/karube1.jfif'
    img.className = 'photo_plot'
    forphoto.appendChild(img)
}
karube.onmouseout = function(){
    document.querySelector('.photo_plot').remove()
}
let cheta = document.getElementById('Cheta')
cheta.onmouseover = function(){
    const forphoto = document.querySelector('#forphoto')
    const img = document.createElement('img')
    img.src = 'img/cheta1.jfif'
    img.className = 'photo_plot'
    forphoto.appendChild(img)
}
cheta.onmouseout = function(){
    document.querySelector('.photo_plot').remove()
}
//section characters
document.getElementById('nameAr').onclick = function(){
    alert("Arisu Ryohei")
}
document.getElementById('nameCh').onclick = function(){
    alert("Cheta Sagawa")
}
document.getElementById('nameChis').onclick = function(){
    alert("Chishiya Shuntaro")
}
document.getElementById('nameKa').onclick = function(){
    alert("Karube Daikichi")
}
document.getElementById('nameNi').onclick = function(){
    alert("Niragi Suguru")
}
document.getElementById('nameUs').onclick = function(){
    alert("Usagi Yuzuha")
}
document.getElementById('nameShl').onclick = function(){
    alert("Danma Takeru (the hatter)")
}
document.getElementById('nameAy').onclick = function(){
    alert("Kuina Hikari")
}
//галерея
const slides = document.querySelectorAll('.slide')
for(const slide of slides) {
    slide.addEventListener('click', () => {
        clearActiveClasses()
        slide.classList.add('active')
    })
}
function clearActiveClasses() {
    slides.forEach((slide) => {
        slide.classList.remove('active')
    })
}



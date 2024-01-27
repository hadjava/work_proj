# work_proj
ссылка на мои проекты на CODEPEN - https://codepen.io/Dmitriy-Khadzhava/pen/dyQKbom

Ванильный JS


const slides = document.querySelectorAll('.slide')

for (const slide of slides) {
   slide.addEventListener('click', () => {
    clearActiveClasses()


    slide.classList.add('active')
   })
}

function clearActiveClasses() {
    slides.forEach((slide) => {
   slide.classList.remove('active')
    } )
}

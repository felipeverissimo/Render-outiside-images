// performace  functions load image outside viewport after render time

const plansImg = document.querySelectorAll('[data-img-src]');
const arrImg = Array.from(plansImg);

let renderOutside = () =>{
arrImg.forEach(index => {
	index.setAttribute('src', index.dataset.imgSrc);
	});
}

let outsideViewport = (img) =>{	
	setTimeout (() => renderOutside(img),1000)

}

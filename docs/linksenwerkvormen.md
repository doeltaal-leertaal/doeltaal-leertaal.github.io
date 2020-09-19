<a href=".."><img src="AFBDTLT.png" id="image"></a>
<style>
#image {
    position: absolute;
    transform: scale(0.3, 0.3);
    right: -150px;
    top: 0px;
}

@media only screen and (max-width: 600px) {
  #image {
  	display: none;
  }
}
	
</style>













<script>

document.getElementById("header").remove();

function remove_subtitle() {
	for(let i = 0; i < 10; i++) {
		for(let j of document.getElementsByClassName("credits")) {
			j.remove();
		}
	}
}


remove_subtitle();
</script>

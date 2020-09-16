# Achtergrond Informatie




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

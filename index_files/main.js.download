$(document).ready(function() {
    $('#formModal .error-block span').fadeOut();
    var aHref = $('#formModalButton').attr("href");

    setTimeout(function() {
    	$('#formModal').fadeIn(200);
        $('#formModalButton').removeAttr("href");
    }, 300);

    $('#formModalButton').click(function() {
        if (($('#formModal input[type="checkbox"]').is(":not(:checked)"))) {
            $('#formModal .error-block span').fadeIn();
        } else {
        	$('#formModal').fadeOut(100);
            $(this).attr('href', aHref);
        }
    });
});

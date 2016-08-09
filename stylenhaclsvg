function music_frame(e) {
    if (1 == /nhaccuatui.com/.test(e)) var a = e.match(/.+.com\/(.+)\/.+/)[1],
        t = {
            playlist: "l",
            "bai-hat": "m",
            video: "video/xem-clip"
        },
        l = e.split(".html")[0],
        l = l.split("."),
        i = l.length - 1,
        l = l[i],
        s = '<object class="music_frame" width="0" height="0"><param name="movie" value="http://www.nhaccuatui.com/' + t[a] + "/" + l + '"><param name="quality" value="high">  <param name="wmode" value="transparent"><param name="allowscriptaccess" value="always"><param name="allowfullscreen" value="true"> <param name="flashvars" value="autostart=true"><embed src="http://www.nhaccuatui.com/' + t[a] + "/" + l + '" flashvars="target=blank&amp;autostart=true" allowscriptaccess="always" allowfullscreen="false" quality="high" wmode="transparent" type="application/x-shockwave-flash" width="0" height="0"></object>';
    if (1 == /youtube.com/.test(e)) var l = e.match(/(?:v=|v\/|embed\/|youtu.be\/)(.{11})/)[1],
        s = '<iframe class="music_frame" width="0" height="0" src="https://www.youtube.com/embed/' + l + '?autoplay=1"></iframe>';
    if (1 == /mp3.zing.vn/.test(e)) var n = e.match(/.+mp3.zing.vn\/(.+)\/.+\/(.+).html/),
        l = n[2],
        a = n[1],
        t = {
            playlist: "album",
            "bai-hat": "song",
            "video-clip": "video"
        },
        s = '<iframe class="music_frame" width="0" height="0" src="http://mp3.zing.vn/embed/' + t[a] + "/" + l + '?autoplay=true"></iframe>';
    $("body").append(s)
}

function checkjson(e) {
    try {
        JSON.parse(e)
    } catch (a) {
        return !1
    }
    return !0
}

function addstyle(e) {
    if (1 == checkjson(e)) {
        var e = e.replace(/\'/gi, '"');
        stylewall = JSON.parse(e);
        var a = '<div id="stylewall"><style>';
        if (a += "#profile-advanced-layout, .dropdown-menu1, .dropdown-menu, .navbar, .main .main-head, .main .main-foot{", a += "background: " + stylewall["color-main-extra"] + "!important;}", a += "</style></div>", $("body").removeClass().append(a), music_frame(stylewall["wall-music"]), 1 == checkimg(stylewall["image-banner-main"])) {
            var t = '<div id="bannerwall"><div id="banner_text"><img src="' + stylewall["image-banner-main"] + '" /></div></div>';
            $(".wall_design").before(t)
        }
    }
}

function test_music() {
    $(".music_wall .submit_icont").removeClass("act"), $(this).addClass("act"), $(".music_frame").remove();
    var e = $('input[name="wall-music"]').val();
    1 == /nhaccuatui.com|mp3.zing.vn|youtube.com/.test(e) && music_frame(e)
}

function off_music() {
    $(".music_wall .submit_icont").removeClass("act"), $(this).addClass("act"), $(".music_frame").remove()
}

function beginstyle(e) {
    $('.col-md-6 [type="text"]').each(function () {
        var a = $(this).attr("name");
        $(this).val(e[a]), $(".music_frame").remove()
    }), $(".image-form").each(function () {
        var e = ($(this).attr("name"), $(this).closest(".pad5")),
            a = $(this).val();
        1 == /\.gif|\.png|\.jpg|\.jpeg|\.bmp/.test(a) ? e.find(".image-preview").html('<img src="' + a + '">') : e.find(".image-preview").html("")
    })
}

function reset_design() {
    void 0 != typeof userstyle ? (stylewall = userstyle, beginstyle(userstyle)) : (stylewall = defaultstyle, beginstyle(defaultstyle)), $("#stylewall,#bannerwall,.music_frame").remove(), $(".snowfall-flakes").length > 0 && $(document).snowfall("clear")
}

function checkimg(e) {
    return 1 == /\.gif|\.png|\.jpg|\.jpeg|\.bmp/.test(e) ? !0 : !1
}

function preview_style() {
    var e = JSON.stringify(stylewall);
    $("#stylewall,#bannerwall,.music_frame").remove(), $(".snowfall-flakes").length > 0 && $(document).snowfall("clear"), addstyle(e)
}

function submit_design() {
    if (1 == submit_change) {
        submit_change = !1;
        var e = JSON.stringify(stylewall);
        $(".loading").fadeIn(500), $("#stylewall,#bannerwall,.music_frame").remove(), $.post("/ajax_profile.forum?jsoncallback=?", {
            id: "2",
            user: _userdata.user_id,
            active: "1",
            content: '[["profile_field_13_1","' + e.replace(/\"/gi, "'") + '"]]',
            tid: $('a[href*="logout="]').attr("href").match(/.+tid\=(.+)\&.+/)[1]
        }, {}, "json").done(function (a) {
            submit_change = !0, $(".loading").fadeOut(500), addstyle(e)
        })
    }
}
var submit_change = !0,
    defaultstyle = {
        "color-main-extra": "#0b8c8c",
        "image-banner-main": "",
        "wall-music": ""
    };
$('.col-md-6 [type="text"]').change(function () {
    var e = $(this).attr("name"),
        a = $(this).closest(".pad5"),
        t = $(this).val();
    1 == /\.gif|\.png|\.jpg|\.jpeg|\.bmp/.test(t) && a.find(".image-preview").html('<img src="' + t + '">'), stylewall[e] = t
}), $('[type="text"]').focusin(function () {
    $(this).closest(".pad5").addClass("focusact")
}), $('[type="text"]').focusout(function () {
    $(this).closest(".pad5").removeClass("focusact")
}), $(".loading").fadeIn(500), $.get("/u" + _userdata.user_id).done(function (e) {
    var a = $(e).find('[id^="field_id"] dt:contains(stylewall)').parent(),
        t = a.find(".field_uneditable").text(),
        t = t.replace(/\'/gi, '"');
    1 == checkjson(t) ? (stylewall = JSON.parse(t), userstyle = stylewall, beginstyle(stylewall)) : (stylewall = defaultstyle, beginstyle(stylewall)), $(".colorpicker-element").minicolors({
        animationSpeed: 50,
        animationEasing: "swing",
        change: null,
        changeDelay: 0,
        control: "hue",
        dataUris: !0,
        defaultValue: "",
        format: "hex",
        hide: null,
        hideSpeed: 100,
        inline: !1,
        keywords: "",
        letterCase: "uppercase",
        opacity: !1,
        position: "bottom left",
        show: null,
        showSpeed: 100,
        theme: "default"
    }), $(".loading").fadeOut(500)
});

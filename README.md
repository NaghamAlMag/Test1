<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script>L_PREFER_CANVAS=false; L_NO_TOUCH=false; L_DISABLE_3D=false;</script>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawgit.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
    <style>#map_35b429a7a5304ceeaa87803d67a0cd86 {
        position: relative;
        width: 100.0%;
        height: 100.0%;
        left: 0.0%;
        top: 0.0%;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.5/d3.min.js"></script>
</head>
<body>    
    
    <div class="folium-map" id="map_35b429a7a5304ceeaa87803d67a0cd86" ></div>
</body>
<script>    
    
    
        var bounds = null;
    

    var map_35b429a7a5304ceeaa87803d67a0cd86 = L.map(
        'map_35b429a7a5304ceeaa87803d67a0cd86', {
        center: [32.892048, -96.871741],
        zoom: 14,
        maxBounds: bounds,
        layers: [],
        worldCopyJump: false,
        crs: L.CRS.EPSG3857,
        zoomControl: true,
        });

    
    
    var tile_layer_41ee45c765714a728b7dea3b1659b8b3 = L.tileLayer(
        'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
        {
        "attribution": null,
        "detectRetina": false,
        "maxNativeZoom": 18,
        "maxZoom": 18,
        "minZoom": 0,
        "noWrap": false,
        "subdomains": "abc"
}).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
    
        var marker_fffed324f29a4d69875b4b169739eac4 = L.marker(
            [32.892048, -96.871741],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_01ceb9555a3c4346a40a9d6043f2c02e = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'black',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_fffed324f29a4d69875b4b169739eac4.setIcon(icon_01ceb9555a3c4346a40a9d6043f2c02e);
            
    
            var popup_672b75d2f6f94c36ac544d4f954dad41 = L.popup({maxWidth: '300'
            
            });

            
                var html_310bf4546ff44f6b867f0cae77ecb70f = $('<div id="html_310bf4546ff44f6b867f0cae77ecb70f" style="width: 100.0%; height: 100.0%;">Location</div>')[0];
                popup_672b75d2f6f94c36ac544d4f954dad41.setContent(html_310bf4546ff44f6b867f0cae77ecb70f);
            

            marker_fffed324f29a4d69875b4b169739eac4.bindPopup(popup_672b75d2f6f94c36ac544d4f954dad41)
            ;

            
        
    

            var circle_e00783f80c074298b9902cae312175db = L.circle(
                [32.892048, -96.871741],
                {
  "bubblingMouseEvents": true,
  "color": "#696969",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#ff0000",
  "fillOpacity": 0.05,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 2000,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
            
    
        var marker_ec272d6899d44b6285ac7cf9ee928346 = L.marker(
            [32.8933181190263, -96.8618881394887],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_6830e4c772734aa9b83fdde045e4c133 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_ec272d6899d44b6285ac7cf9ee928346.setIcon(icon_6830e4c772734aa9b83fdde045e4c133);
            
    
            var popup_3327afd1b4b841f5b724842e58b10357 = L.popup({maxWidth: '300'
            
            });

            
                var html_dc50dc69699b4d328d051ec7c5636c32 = $('<div id="html_dc50dc69699b4d328d051ec7c5636c32" style="width: 100.0%; height: 100.0%;">$33</div>')[0];
                popup_3327afd1b4b841f5b724842e58b10357.setContent(html_dc50dc69699b4d328d051ec7c5636c32);
            

            marker_ec272d6899d44b6285ac7cf9ee928346.bindPopup(popup_3327afd1b4b841f5b724842e58b10357)
            ;

            
        
    
        var marker_4d971e74c783420a88cf2cb6a28fa567 = L.marker(
            [32.8949295039901, -96.86206701896309],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_62a1c388e6154ba3a139fea3ef1dfaf8 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_4d971e74c783420a88cf2cb6a28fa567.setIcon(icon_62a1c388e6154ba3a139fea3ef1dfaf8);
            
    
            var popup_04d633210d4d47ee9883b7b3745a5391 = L.popup({maxWidth: '300'
            
            });

            
                var html_363ecb16603e4fa6bcf4ab196f8524a3 = $('<div id="html_363ecb16603e4fa6bcf4ab196f8524a3" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_04d633210d4d47ee9883b7b3745a5391.setContent(html_363ecb16603e4fa6bcf4ab196f8524a3);
            

            marker_4d971e74c783420a88cf2cb6a28fa567.bindPopup(popup_04d633210d4d47ee9883b7b3745a5391)
            ;

            
        
    
        var marker_76afe0dc6f7c435990f08acd1a109181 = L.marker(
            [32.8820233239255, -96.87511098155849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_9f5ed9846ded4b4abf4b6f94dbe99aeb = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_76afe0dc6f7c435990f08acd1a109181.setIcon(icon_9f5ed9846ded4b4abf4b6f94dbe99aeb);
            
    
            var popup_827b74bcad3d491a83db999dbaad3076 = L.popup({maxWidth: '300'
            
            });

            
                var html_7f020bd5ef1f4d64841855bfd7ed0daa = $('<div id="html_7f020bd5ef1f4d64841855bfd7ed0daa" style="width: 100.0%; height: 100.0%;">$1000</div>')[0];
                popup_827b74bcad3d491a83db999dbaad3076.setContent(html_7f020bd5ef1f4d64841855bfd7ed0daa);
            

            marker_76afe0dc6f7c435990f08acd1a109181.bindPopup(popup_827b74bcad3d491a83db999dbaad3076)
            ;

            
        
    
        var marker_f9e54984f16a4426a53b720325e8e10a = L.marker(
            [32.9077810249579, -96.8621826243898],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_998ceeb5b57c499fa26020aa2ab4a64a = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_f9e54984f16a4426a53b720325e8e10a.setIcon(icon_998ceeb5b57c499fa26020aa2ab4a64a);
            
    
            var popup_e8e739a060404882b0acbf46f81fb8a5 = L.popup({maxWidth: '300'
            
            });

            
                var html_983b11eed45245adb232d442aee0f710 = $('<div id="html_983b11eed45245adb232d442aee0f710" style="width: 100.0%; height: 100.0%;">$369</div>')[0];
                popup_e8e739a060404882b0acbf46f81fb8a5.setContent(html_983b11eed45245adb232d442aee0f710);
            

            marker_f9e54984f16a4426a53b720325e8e10a.bindPopup(popup_e8e739a060404882b0acbf46f81fb8a5)
            ;

            
        
    
        var marker_5915dc70a64e4239adcb1c176ec415da = L.marker(
            [32.8944793226889, -96.85326030618401],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_0cbc9b05bd364e43b2324d087a8d05b4 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_5915dc70a64e4239adcb1c176ec415da.setIcon(icon_0cbc9b05bd364e43b2324d087a8d05b4);
            
    
            var popup_3d189825861d413786444300c0d3c5d8 = L.popup({maxWidth: '300'
            
            });

            
                var html_aadd32613e9e41209aced4afe71b79b7 = $('<div id="html_aadd32613e9e41209aced4afe71b79b7" style="width: 100.0%; height: 100.0%;">$49</div>')[0];
                popup_3d189825861d413786444300c0d3c5d8.setContent(html_aadd32613e9e41209aced4afe71b79b7);
            

            marker_5915dc70a64e4239adcb1c176ec415da.bindPopup(popup_3d189825861d413786444300c0d3c5d8)
            ;

            
        
    
        var marker_2f4e1e11d7294fb5abdf2996c98c6fca = L.marker(
            [32.8969128016987, -96.8695319039417],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_31390bcb3b37457299cbdfbbd5804ba8 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_2f4e1e11d7294fb5abdf2996c98c6fca.setIcon(icon_31390bcb3b37457299cbdfbbd5804ba8);
            
    
            var popup_73b6cbf3ac9941e1ad402cbfa28ea738 = L.popup({maxWidth: '300'
            
            });

            
                var html_5fa407c8cc6944d695359741bf906aa2 = $('<div id="html_5fa407c8cc6944d695359741bf906aa2" style="width: 100.0%; height: 100.0%;">$40</div>')[0];
                popup_73b6cbf3ac9941e1ad402cbfa28ea738.setContent(html_5fa407c8cc6944d695359741bf906aa2);
            

            marker_2f4e1e11d7294fb5abdf2996c98c6fca.bindPopup(popup_73b6cbf3ac9941e1ad402cbfa28ea738)
            ;

            
        
    
        var marker_6a71b2a055154ad2884cc286ed819285 = L.marker(
            [32.901805911191104, -96.86800149482849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_82579672e224452cba16be8031c18c1b = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_6a71b2a055154ad2884cc286ed819285.setIcon(icon_82579672e224452cba16be8031c18c1b);
            
    
            var popup_8621f4d04abb43ffbde4de360f6c8907 = L.popup({maxWidth: '300'
            
            });

            
                var html_05e1897b0ace4c4994895d4ef2950211 = $('<div id="html_05e1897b0ace4c4994895d4ef2950211" style="width: 100.0%; height: 100.0%;">$67</div>')[0];
                popup_8621f4d04abb43ffbde4de360f6c8907.setContent(html_05e1897b0ace4c4994895d4ef2950211);
            

            marker_6a71b2a055154ad2884cc286ed819285.bindPopup(popup_8621f4d04abb43ffbde4de360f6c8907)
            ;

            
        
    
        var marker_ca2d4fb78d894e99aacb52f0b59c42d2 = L.marker(
            [32.9031087655529, -96.8667337476207],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_e7f0a8f4650148f390cbc796e43b1253 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_ca2d4fb78d894e99aacb52f0b59c42d2.setIcon(icon_e7f0a8f4650148f390cbc796e43b1253);
            
    
            var popup_68d2b5a3ccd44ab1b322ccaed630aa10 = L.popup({maxWidth: '300'
            
            });

            
                var html_8e861b5fe8e04721a5970689696aa087 = $('<div id="html_8e861b5fe8e04721a5970689696aa087" style="width: 100.0%; height: 100.0%;">$95</div>')[0];
                popup_68d2b5a3ccd44ab1b322ccaed630aa10.setContent(html_8e861b5fe8e04721a5970689696aa087);
            

            marker_ca2d4fb78d894e99aacb52f0b59c42d2.bindPopup(popup_68d2b5a3ccd44ab1b322ccaed630aa10)
            ;

            
        
    
        var marker_fc3e6feb764f4dffad23e491387aeae0 = L.marker(
            [32.8852465509118, -96.87014674082121],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_05e6c64891364725ac5bb429dda6cc47 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_fc3e6feb764f4dffad23e491387aeae0.setIcon(icon_05e6c64891364725ac5bb429dda6cc47);
            
    
            var popup_18ebd8636de8435fa6211dc9d44ad255 = L.popup({maxWidth: '300'
            
            });

            
                var html_3d5aa169feb24d369ff6c982f6fdd1ce = $('<div id="html_3d5aa169feb24d369ff6c982f6fdd1ce" style="width: 100.0%; height: 100.0%;">$75</div>')[0];
                popup_18ebd8636de8435fa6211dc9d44ad255.setContent(html_3d5aa169feb24d369ff6c982f6fdd1ce);
            

            marker_fc3e6feb764f4dffad23e491387aeae0.bindPopup(popup_18ebd8636de8435fa6211dc9d44ad255)
            ;

            
        
    
        var marker_3e89feb348e54645871f1b15166cb77a = L.marker(
            [32.883227682540806, -96.86105138861559],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_50c5e8f97bb748dcb0e0af085cf5976c = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_3e89feb348e54645871f1b15166cb77a.setIcon(icon_50c5e8f97bb748dcb0e0af085cf5976c);
            
    
            var popup_afee9dcd6a5e447e9f42f059627d54cc = L.popup({maxWidth: '300'
            
            });

            
                var html_2d0ed5dbfcd4452ba6376a40f88f62f8 = $('<div id="html_2d0ed5dbfcd4452ba6376a40f88f62f8" style="width: 100.0%; height: 100.0%;">$394</div>')[0];
                popup_afee9dcd6a5e447e9f42f059627d54cc.setContent(html_2d0ed5dbfcd4452ba6376a40f88f62f8);
            

            marker_3e89feb348e54645871f1b15166cb77a.bindPopup(popup_afee9dcd6a5e447e9f42f059627d54cc)
            ;

            
        
    
        var marker_13670dd6cc7a464eaf1899f3b0412f32 = L.marker(
            [32.877256063740894, -96.8757989788942],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_f709b25d9e1a4cf08888db69d50747d5 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_13670dd6cc7a464eaf1899f3b0412f32.setIcon(icon_f709b25d9e1a4cf08888db69d50747d5);
            
    
            var popup_a4a47ab88f28486f986ec4c6f36b1260 = L.popup({maxWidth: '300'
            
            });

            
                var html_84f4434654bd4dae9104bf952cb01908 = $('<div id="html_84f4434654bd4dae9104bf952cb01908" style="width: 100.0%; height: 100.0%;">$85</div>')[0];
                popup_a4a47ab88f28486f986ec4c6f36b1260.setContent(html_84f4434654bd4dae9104bf952cb01908);
            

            marker_13670dd6cc7a464eaf1899f3b0412f32.bindPopup(popup_a4a47ab88f28486f986ec4c6f36b1260)
            ;

            
        
    
        var marker_39ab50467f304fafbca8163426e0b176 = L.marker(
            [32.8981462981182, -96.8586509057892],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_6cbf30c99a8847f2858766ec6ea2659a = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_39ab50467f304fafbca8163426e0b176.setIcon(icon_6cbf30c99a8847f2858766ec6ea2659a);
            
    
            var popup_e4faa9b808634ab980de09ed57f3345c = L.popup({maxWidth: '300'
            
            });

            
                var html_b52c35502e324aa0b875acd6668ff524 = $('<div id="html_b52c35502e324aa0b875acd6668ff524" style="width: 100.0%; height: 100.0%;">$80</div>')[0];
                popup_e4faa9b808634ab980de09ed57f3345c.setContent(html_b52c35502e324aa0b875acd6668ff524);
            

            marker_39ab50467f304fafbca8163426e0b176.bindPopup(popup_e4faa9b808634ab980de09ed57f3345c)
            ;

            
        
    
        var marker_79d918901f964e3fb88e3c68c068f4a8 = L.marker(
            [32.9040282448911, -96.86996727735821],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_80121ceb2d944493b8dc2d477f1c9576 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_79d918901f964e3fb88e3c68c068f4a8.setIcon(icon_80121ceb2d944493b8dc2d477f1c9576);
            
    
            var popup_f67250e7e2204d22b720a29af77d39d2 = L.popup({maxWidth: '300'
            
            });

            
                var html_3476daeaf3db4f3fa3bb8398512e230d = $('<div id="html_3476daeaf3db4f3fa3bb8398512e230d" style="width: 100.0%; height: 100.0%;">$50</div>')[0];
                popup_f67250e7e2204d22b720a29af77d39d2.setContent(html_3476daeaf3db4f3fa3bb8398512e230d);
            

            marker_79d918901f964e3fb88e3c68c068f4a8.bindPopup(popup_f67250e7e2204d22b720a29af77d39d2)
            ;

            
        
    
        var marker_a593549dc1bd4f54928233d524ca1610 = L.marker(
            [32.8771344812899, -96.86328393723329],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_c014c88a99e64bb88f990dacdcbfda48 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'purple',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_a593549dc1bd4f54928233d524ca1610.setIcon(icon_c014c88a99e64bb88f990dacdcbfda48);
            
    
            var popup_21334c5234d7437495ec529f996ec85e = L.popup({maxWidth: '300'
            
            });

            
                var html_d83228c94b104b6d95cf2a7ac63b1970 = $('<div id="html_d83228c94b104b6d95cf2a7ac63b1970" style="width: 100.0%; height: 100.0%;">$165</div>')[0];
                popup_21334c5234d7437495ec529f996ec85e.setContent(html_d83228c94b104b6d95cf2a7ac63b1970);
            

            marker_a593549dc1bd4f54928233d524ca1610.bindPopup(popup_21334c5234d7437495ec529f996ec85e)
            ;

            
        
    
        var marker_623eb37405ef4423a15f2a9bb11db5d4 = L.marker(
            [32.8920481255171, -96.8717408122603],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_bd9900c69bbc4c2faf8d8c468b701232 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_623eb37405ef4423a15f2a9bb11db5d4.setIcon(icon_bd9900c69bbc4c2faf8d8c468b701232);
            
    
            var popup_05fde47f63fc4370ab847a813a82174f = L.popup({maxWidth: '300'
            
            });

            
                var html_9d7f403d239b4a94aefe9243844b763c = $('<div id="html_9d7f403d239b4a94aefe9243844b763c" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_05fde47f63fc4370ab847a813a82174f.setContent(html_9d7f403d239b4a94aefe9243844b763c);
            

            marker_623eb37405ef4423a15f2a9bb11db5d4.bindPopup(popup_05fde47f63fc4370ab847a813a82174f)
            ;

            
        
    
    var color_map_44b3bb0103df4bccb599eec34889abd9 = {};

    
    color_map_44b3bb0103df4bccb599eec34889abd9.color = d3.scale.threshold()
              .domain([0.0, 2.004008016032064, 4.008016032064128, 6.012024048096192, 8.016032064128256, 10.02004008016032, 12.024048096192384, 14.02805611222445, 16.03206412825651, 18.03607214428858, 20.04008016032064, 22.044088176352705, 24.04809619238477, 26.052104208416832, 28.0561122244489, 30.060120240480963, 32.06412825651302, 34.06813627254509, 36.07214428857716, 38.07615230460922, 40.08016032064128, 42.08416833667334, 44.08817635270541, 46.09218436873748, 48.09619238476954, 50.100200400801604, 52.104208416833664, 54.10821643286573, 56.1122244488978, 58.11623246492986, 60.120240480961925, 62.124248496993985, 64.12825651302605, 66.13226452905812, 68.13627254509018, 70.14028056112224, 72.14428857715431, 74.14829659318637, 76.15230460921843, 78.15631262525051, 80.16032064128257, 82.16432865731463, 84.16833667334669, 86.17234468937876, 88.17635270541082, 90.18036072144288, 92.18436873747495, 94.18837675350701, 96.19238476953907, 98.19639278557115, 100.20040080160321, 102.20440881763527, 104.20841683366733, 106.2124248496994, 108.21643286573146, 110.22044088176352, 112.2244488977956, 114.22845691382766, 116.23246492985972, 118.23647294589178, 120.24048096192385, 122.24448897795591, 124.24849699398797, 126.25250501002004, 128.2565130260521, 130.26052104208418, 132.26452905811624, 134.2685370741483, 136.27254509018036, 138.27655310621242, 140.28056112224448, 142.28456913827657, 144.28857715430863, 146.2925851703407, 148.29659318637275, 150.3006012024048, 152.30460921843687, 154.30861723446893, 156.31262525050101, 158.31663326653307, 160.32064128256513, 162.3246492985972, 164.32865731462925, 166.3326653306613, 168.33667334669337, 170.34068136272546, 172.34468937875752, 174.34869739478958, 176.35270541082164, 178.3567134268537, 180.36072144288576, 182.36472945891782, 184.3687374749499, 186.37274549098197, 188.37675350701403, 190.3807615230461, 192.38476953907815, 194.3887775551102, 196.3927855711423, 198.39679358717436, 200.40080160320642, 202.40480961923848, 204.40881763527054, 206.4128256513026, 208.41683366733466, 210.42084168336675, 212.4248496993988, 214.42885771543087, 216.43286573146293, 218.43687374749499, 220.44088176352705, 222.4448897795591, 224.4488977955912, 226.45290581162325, 228.4569138276553, 230.46092184368737, 232.46492985971943, 234.4689378757515, 236.47294589178355, 238.47695390781564, 240.4809619238477, 242.48496993987976, 244.48897795591182, 246.49298597194388, 248.49699398797594, 250.50100200400803, 252.5050100200401, 254.50901803607215, 256.5130260521042, 258.5170340681363, 260.52104208416836, 262.5250501002004, 264.5290581162325, 266.53306613226454, 268.5370741482966, 270.54108216432866, 272.5450901803607, 274.5490981963928, 276.55310621242484, 278.5571142284569, 280.56112224448896, 282.565130260521, 284.56913827655313, 286.5731462925852, 288.57715430861725, 290.5811623246493, 292.5851703406814, 294.58917835671343, 296.5931863727455, 298.59719438877755, 300.6012024048096, 302.6052104208417, 304.60921843687373, 306.6132264529058, 308.61723446893785, 310.6212424849699, 312.62525050100203, 314.6292585170341, 316.63326653306615, 318.6372745490982, 320.64128256513027, 322.6452905811623, 324.6492985971944, 326.65330661322645, 328.6573146292585, 330.66132264529057, 332.6653306613226, 334.6693386773547, 336.67334669338675, 338.67735470941886, 340.6813627254509, 342.685370741483, 344.68937875751504, 346.6933867735471, 348.69739478957916, 350.7014028056112, 352.7054108216433, 354.70941883767534, 356.7134268537074, 358.71743486973946, 360.7214428857715, 362.7254509018036, 364.72945891783564, 366.73346693386776, 368.7374749498998, 370.7414829659319, 372.74549098196394, 374.749498997996, 376.75350701402806, 378.7575150300601, 380.7615230460922, 382.76553106212424, 384.7695390781563, 386.77354709418836, 388.7775551102204, 390.7815631262525, 392.7855711422846, 394.78957915831666, 396.7935871743487, 398.7975951903808, 400.80160320641284, 402.8056112224449, 404.80961923847696, 406.813627254509, 408.8176352705411, 410.82164328657313, 412.8256513026052, 414.82965931863725, 416.8336673346693, 418.8376753507014, 420.8416833667335, 422.84569138276555, 424.8496993987976, 426.85370741482967, 428.85771543086173, 430.8617234468938, 432.86573146292585, 434.8697394789579, 436.87374749498997, 438.87775551102203, 440.8817635270541, 442.88577154308615, 444.8897795591182, 446.8937875751503, 448.8977955911824, 450.90180360721445, 452.9058116232465, 454.90981963927857, 456.9138276553106, 458.9178356713427, 460.92184368737475, 462.9258517034068, 464.92985971943887, 466.9338677354709, 468.937875751503, 470.94188376753505, 472.9458917835671, 474.9498997995992, 476.9539078156313, 478.95791583166334, 480.9619238476954, 482.96593186372746, 484.9699398797595, 486.9739478957916, 488.97795591182364, 490.9819639278557, 492.98597194388776, 494.9899799599198, 496.9939879759519, 498.99799599198394, 501.00200400801606, 503.0060120240481, 505.0100200400802, 507.01402805611224, 509.0180360721443, 511.02204408817636, 513.0260521042084, 515.0300601202405, 517.0340681362726, 519.0380761523046, 521.0420841683367, 523.0460921843687, 525.0501002004008, 527.0541082164328, 529.058116232465, 531.062124248497, 533.0661322645291, 535.0701402805611, 537.0741482965932, 539.0781563126252, 541.0821643286573, 543.0861723446894, 545.0901803607214, 547.0941883767536, 549.0981963927856, 551.1022044088177, 553.1062124248497, 555.1102204408818, 557.1142284569138, 559.1182364729459, 561.1222444889779, 563.12625250501, 565.130260521042, 567.1342685370741, 569.1382765531063, 571.1422845691383, 573.1462925851704, 575.1503006012024, 577.1543086172345, 579.1583166332665, 581.1623246492986, 583.1663326653306, 585.1703406813627, 587.1743486973947, 589.1783567134269, 591.1823647294589, 593.186372745491, 595.1903807615231, 597.1943887775551, 599.1983967935872, 601.2024048096192, 603.2064128256513, 605.2104208416833, 607.2144288577155, 609.2184368737475, 611.2224448897796, 613.2264529058116, 615.2304609218437, 617.2344689378757, 619.2384769539078, 621.2424849699398, 623.2464929859719, 625.2505010020041, 627.2545090180361, 629.2585170340682, 631.2625250501002, 633.2665330661323, 635.2705410821643, 637.2745490981964, 639.2785571142284, 641.2825651302605, 643.2865731462925, 645.2905811623247, 647.2945891783567, 649.2985971943888, 651.3026052104209, 653.3066132264529, 655.310621242485, 657.314629258517, 659.3186372745491, 661.3226452905811, 663.3266533066133, 665.3306613226453, 667.3346693386774, 669.3386773547094, 671.3426853707415, 673.3466933867735, 675.3507014028056, 677.3547094188377, 679.3587174348697, 681.3627254509018, 683.3667334669339, 685.370741482966, 687.374749498998, 689.3787575150301, 691.3827655310621, 693.3867735470942, 695.3907815631262, 697.3947895791583, 699.3987975951903, 701.4028056112224, 703.4068136272546, 705.4108216432866, 707.4148296593187, 709.4188376753507, 711.4228456913828, 713.4268537074148, 715.4308617234469, 717.4348697394789, 719.438877755511, 721.442885771543, 723.4468937875752, 725.4509018036072, 727.4549098196393, 729.4589178356713, 731.4629258517034, 733.4669338677355, 735.4709418837675, 737.4749498997996, 739.4789579158316, 741.4829659318638, 743.4869739478958, 745.4909819639279, 747.4949899799599, 749.498997995992, 751.503006012024, 753.5070140280561, 755.5110220440881, 757.5150300601202, 759.5190380761524, 761.5230460921844, 763.5270541082165, 765.5310621242485, 767.5350701402806, 769.5390781563126, 771.5430861723447, 773.5470941883767, 775.5511022044088, 777.5551102204408, 779.559118236473, 781.563126252505, 783.5671342685371, 785.5711422845692, 787.5751503006012, 789.5791583166333, 791.5831663326653, 793.5871743486974, 795.5911823647294, 797.5951903807616, 799.5991983967936, 801.6032064128257, 803.6072144288577, 805.6112224448898, 807.6152304609218, 809.6192384769539, 811.623246492986, 813.627254509018, 815.6312625250501, 817.6352705410821, 819.6392785571143, 821.6432865731463, 823.6472945891784, 825.6513026052104, 827.6553106212425, 829.6593186372745, 831.6633266533066, 833.6673346693386, 835.6713426853707, 837.6753507014027, 839.6793587174349, 841.683366733467, 843.687374749499, 845.6913827655311, 847.6953907815631, 849.6993987975952, 851.7034068136272, 853.7074148296593, 855.7114228456913, 857.7154308617235, 859.7194388777555, 861.7234468937876, 863.7274549098196, 865.7314629258517, 867.7354709418838, 869.7394789579158, 871.7434869739479, 873.7474949899799, 875.7515030060121, 877.7555110220441, 879.7595190380762, 881.7635270541082, 883.7675350701403, 885.7715430861723, 887.7755511022044, 889.7795591182364, 891.7835671342685, 893.7875751503007, 895.7915831663327, 897.7955911823648, 899.7995991983968, 901.8036072144289, 903.8076152304609, 905.811623246493, 907.815631262525, 909.8196392785571, 911.8236472945891, 913.8276553106213, 915.8316633266533, 917.8356713426854, 919.8396793587175, 921.8436873747495, 923.8476953907816, 925.8517034068136, 927.8557114228457, 929.8597194388777, 931.8637274549098, 933.8677354709419, 935.871743486974, 937.875751503006, 939.8797595190381, 941.8837675350701, 943.8877755511022, 945.8917835671342, 947.8957915831663, 949.8997995991984, 951.9038076152304, 953.9078156312626, 955.9118236472946, 957.9158316633267, 959.9198396793587, 961.9238476953908, 963.9278557114228, 965.9318637274549, 967.9358717434869, 969.939879759519, 971.943887775551, 973.9478957915832, 975.9519038076153, 977.9559118236473, 979.9599198396794, 981.9639278557114, 983.9679358717435, 985.9719438877755, 987.9759519038076, 989.9799599198396, 991.9839679358718, 993.9879759519038, 995.9919839679359, 997.9959919839679, 1000.0])
              .range(['#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#ff0000', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#0000ff', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#800080', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb', '#ffc0cb']);
    

    color_map_44b3bb0103df4bccb599eec34889abd9.x = d3.scale.linear()
              .domain([0.0, 1000.0])
              .range([0, 400]);

    color_map_44b3bb0103df4bccb599eec34889abd9.legend = L.control({position: 'topright'});
    color_map_44b3bb0103df4bccb599eec34889abd9.legend.onAdd = function (map) {var div = L.DomUtil.create('div', 'legend'); return div};
    color_map_44b3bb0103df4bccb599eec34889abd9.legend.addTo(map_35b429a7a5304ceeaa87803d67a0cd86);

    color_map_44b3bb0103df4bccb599eec34889abd9.xAxis = d3.svg.axis()
        .scale(color_map_44b3bb0103df4bccb599eec34889abd9.x)
        .orient("top")
        .tickSize(1)
        .tickValues([0, 350, 700, 800]);

    color_map_44b3bb0103df4bccb599eec34889abd9.svg = d3.select(".legend.leaflet-control").append("svg")
        .attr("id", 'legend')
        .attr("width", 450)
        .attr("height", 40);

    color_map_44b3bb0103df4bccb599eec34889abd9.g = color_map_44b3bb0103df4bccb599eec34889abd9.svg.append("g")
        .attr("class", "key")
        .attr("transform", "translate(25,16)");

    color_map_44b3bb0103df4bccb599eec34889abd9.g.selectAll("rect")
        .data(color_map_44b3bb0103df4bccb599eec34889abd9.color.range().map(function(d, i) {
          return {
            x0: i ? color_map_44b3bb0103df4bccb599eec34889abd9.x(color_map_44b3bb0103df4bccb599eec34889abd9.color.domain()[i - 1]) : color_map_44b3bb0103df4bccb599eec34889abd9.x.range()[0],
            x1: i < color_map_44b3bb0103df4bccb599eec34889abd9.color.domain().length ? color_map_44b3bb0103df4bccb599eec34889abd9.x(color_map_44b3bb0103df4bccb599eec34889abd9.color.domain()[i]) : color_map_44b3bb0103df4bccb599eec34889abd9.x.range()[1],
            z: d
          };
        }))
      .enter().append("rect")
        .attr("height", 10)
        .attr("x", function(d) { return d.x0; })
        .attr("width", function(d) { return d.x1 - d.x0; })
        .style("fill", function(d) { return d.z; });

    color_map_44b3bb0103df4bccb599eec34889abd9.g.call(color_map_44b3bb0103df4bccb599eec34889abd9.xAxis).append("text")
        .attr("class", "caption")
        .attr("y", 21)
        .text(' divided by Price');
    
        var marker_597fce8066d34ba5b14b8ce41e58d9fa = L.marker(
            [32.892048, -96.871741],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_0969928497c74715acd282447bf0bc85 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'black',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_597fce8066d34ba5b14b8ce41e58d9fa.setIcon(icon_0969928497c74715acd282447bf0bc85);
            
    
            var popup_6111d80368c54b56bdab009bc3f9781b = L.popup({maxWidth: '300'
            
            });

            
                var html_4a1418a54e0f46489075e7c70ca66bea = $('<div id="html_4a1418a54e0f46489075e7c70ca66bea" style="width: 100.0%; height: 100.0%;">Location</div>')[0];
                popup_6111d80368c54b56bdab009bc3f9781b.setContent(html_4a1418a54e0f46489075e7c70ca66bea);
            

            marker_597fce8066d34ba5b14b8ce41e58d9fa.bindPopup(popup_6111d80368c54b56bdab009bc3f9781b)
            ;

            
        
    

            var circle_a3fb4187e741470b9b4e2b2c433bafde = L.circle(
                [32.892048, -96.871741],
                {
  "bubblingMouseEvents": true,
  "color": "#696969",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#ff0000",
  "fillOpacity": 0.05,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 2000,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
            
    
        var marker_5eb4bde351614af0bea8ba623bb29ce0 = L.marker(
            [32.8933181190263, -96.8618881394887],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_e3675b3032124f639fcf9c2f6031118f = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_5eb4bde351614af0bea8ba623bb29ce0.setIcon(icon_e3675b3032124f639fcf9c2f6031118f);
            
    
            var popup_fb1a1f546dc4414eaf579fa40d070b64 = L.popup({maxWidth: '300'
            
            });

            
                var html_dc507eabed674370a43a24382bc0aae3 = $('<div id="html_dc507eabed674370a43a24382bc0aae3" style="width: 100.0%; height: 100.0%;">$33</div>')[0];
                popup_fb1a1f546dc4414eaf579fa40d070b64.setContent(html_dc507eabed674370a43a24382bc0aae3);
            

            marker_5eb4bde351614af0bea8ba623bb29ce0.bindPopup(popup_fb1a1f546dc4414eaf579fa40d070b64)
            ;

            
        
    
        var marker_2a4c2b8ca8b24adc8e56549ca41f2d52 = L.marker(
            [32.8949295039901, -96.86206701896309],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_44cfe95537704b2ebfdbf3a880a643aa = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_2a4c2b8ca8b24adc8e56549ca41f2d52.setIcon(icon_44cfe95537704b2ebfdbf3a880a643aa);
            
    
            var popup_75ed2d67f41f486baed9304a9b84f062 = L.popup({maxWidth: '300'
            
            });

            
                var html_9b977a0565844c578dfafcc2ae512548 = $('<div id="html_9b977a0565844c578dfafcc2ae512548" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_75ed2d67f41f486baed9304a9b84f062.setContent(html_9b977a0565844c578dfafcc2ae512548);
            

            marker_2a4c2b8ca8b24adc8e56549ca41f2d52.bindPopup(popup_75ed2d67f41f486baed9304a9b84f062)
            ;

            
        
    
        var marker_19a4e5dff83541678593dea68b55232e = L.marker(
            [32.8820233239255, -96.87511098155849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_ca30a8d3d8d24aa48d7242f39fa20585 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_19a4e5dff83541678593dea68b55232e.setIcon(icon_ca30a8d3d8d24aa48d7242f39fa20585);
            
    
            var popup_c5b07bb3849c4e8bb3074592a821ce22 = L.popup({maxWidth: '300'
            
            });

            
                var html_fe26f6830a7e4e1d8a3f3fe32875d728 = $('<div id="html_fe26f6830a7e4e1d8a3f3fe32875d728" style="width: 100.0%; height: 100.0%;">$1000</div>')[0];
                popup_c5b07bb3849c4e8bb3074592a821ce22.setContent(html_fe26f6830a7e4e1d8a3f3fe32875d728);
            

            marker_19a4e5dff83541678593dea68b55232e.bindPopup(popup_c5b07bb3849c4e8bb3074592a821ce22)
            ;

            
        
    
        var marker_aa431df0ac9e498ca5272a6a153fd4bb = L.marker(
            [32.9077810249579, -96.8621826243898],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_0a21a2da2ce34b86bd54ba0145a17932 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_aa431df0ac9e498ca5272a6a153fd4bb.setIcon(icon_0a21a2da2ce34b86bd54ba0145a17932);
            
    
            var popup_8cb5658e7cb347f8937ee476f3c951bc = L.popup({maxWidth: '300'
            
            });

            
                var html_da72cdca68664ab3a36e3866478ebd7c = $('<div id="html_da72cdca68664ab3a36e3866478ebd7c" style="width: 100.0%; height: 100.0%;">$369</div>')[0];
                popup_8cb5658e7cb347f8937ee476f3c951bc.setContent(html_da72cdca68664ab3a36e3866478ebd7c);
            

            marker_aa431df0ac9e498ca5272a6a153fd4bb.bindPopup(popup_8cb5658e7cb347f8937ee476f3c951bc)
            ;

            
        
    
        var marker_38213eedd5dd465b8b32cd9d8cca189c = L.marker(
            [32.8944793226889, -96.85326030618401],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_61e6fdfd44a444ae9a8a521086232c91 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_38213eedd5dd465b8b32cd9d8cca189c.setIcon(icon_61e6fdfd44a444ae9a8a521086232c91);
            
    
            var popup_48b1df4040544e608e744b9680aa02bc = L.popup({maxWidth: '300'
            
            });

            
                var html_d4034a587165481ea28f529cf145e871 = $('<div id="html_d4034a587165481ea28f529cf145e871" style="width: 100.0%; height: 100.0%;">$49</div>')[0];
                popup_48b1df4040544e608e744b9680aa02bc.setContent(html_d4034a587165481ea28f529cf145e871);
            

            marker_38213eedd5dd465b8b32cd9d8cca189c.bindPopup(popup_48b1df4040544e608e744b9680aa02bc)
            ;

            
        
    
        var marker_14a45c8f427a48469f663b41431681bb = L.marker(
            [32.8969128016987, -96.8695319039417],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_8cc6e6289aac4ac8b043ef247b113549 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_14a45c8f427a48469f663b41431681bb.setIcon(icon_8cc6e6289aac4ac8b043ef247b113549);
            
    
            var popup_96a3f424d4d24a5bb11c5e9b0cf3dfa9 = L.popup({maxWidth: '300'
            
            });

            
                var html_75ea903229f640438ab0f02adc3b7f4b = $('<div id="html_75ea903229f640438ab0f02adc3b7f4b" style="width: 100.0%; height: 100.0%;">$40</div>')[0];
                popup_96a3f424d4d24a5bb11c5e9b0cf3dfa9.setContent(html_75ea903229f640438ab0f02adc3b7f4b);
            

            marker_14a45c8f427a48469f663b41431681bb.bindPopup(popup_96a3f424d4d24a5bb11c5e9b0cf3dfa9)
            ;

            
        
    
        var marker_7240aaf2e64a41d685dab312a102b486 = L.marker(
            [32.901805911191104, -96.86800149482849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_9f494030897244b9b623c53a5a1f4575 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_7240aaf2e64a41d685dab312a102b486.setIcon(icon_9f494030897244b9b623c53a5a1f4575);
            
    
            var popup_dcac4b212255427ab527c4e49cca21c6 = L.popup({maxWidth: '300'
            
            });

            
                var html_fe916b10a41e44f6b6b9a7c54c25322e = $('<div id="html_fe916b10a41e44f6b6b9a7c54c25322e" style="width: 100.0%; height: 100.0%;">$67</div>')[0];
                popup_dcac4b212255427ab527c4e49cca21c6.setContent(html_fe916b10a41e44f6b6b9a7c54c25322e);
            

            marker_7240aaf2e64a41d685dab312a102b486.bindPopup(popup_dcac4b212255427ab527c4e49cca21c6)
            ;

            
        
    
        var marker_dfa694ab18ce419b8f713d5c9fc92db0 = L.marker(
            [32.9031087655529, -96.8667337476207],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_e6daa61ce4f1450997930e64186bc426 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_dfa694ab18ce419b8f713d5c9fc92db0.setIcon(icon_e6daa61ce4f1450997930e64186bc426);
            
    
            var popup_b344ead4fe1f450b9e3ca21364d5b6a4 = L.popup({maxWidth: '300'
            
            });

            
                var html_77b21979bac54202a7b6278f80cade2c = $('<div id="html_77b21979bac54202a7b6278f80cade2c" style="width: 100.0%; height: 100.0%;">$95</div>')[0];
                popup_b344ead4fe1f450b9e3ca21364d5b6a4.setContent(html_77b21979bac54202a7b6278f80cade2c);
            

            marker_dfa694ab18ce419b8f713d5c9fc92db0.bindPopup(popup_b344ead4fe1f450b9e3ca21364d5b6a4)
            ;

            
        
    
        var marker_b17cbfac870a499a872d816f88451226 = L.marker(
            [32.8852465509118, -96.87014674082121],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_9ec90cdb39d548c383fd1f070db11319 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_b17cbfac870a499a872d816f88451226.setIcon(icon_9ec90cdb39d548c383fd1f070db11319);
            
    
            var popup_9e6476fd8da74a02bd2a5f3757932ac9 = L.popup({maxWidth: '300'
            
            });

            
                var html_29376258809243d88281efe0fbb21a24 = $('<div id="html_29376258809243d88281efe0fbb21a24" style="width: 100.0%; height: 100.0%;">$75</div>')[0];
                popup_9e6476fd8da74a02bd2a5f3757932ac9.setContent(html_29376258809243d88281efe0fbb21a24);
            

            marker_b17cbfac870a499a872d816f88451226.bindPopup(popup_9e6476fd8da74a02bd2a5f3757932ac9)
            ;

            
        
    
        var marker_1acbd565184940b397749fc75bbcfbe4 = L.marker(
            [32.883227682540806, -96.86105138861559],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_bb2d00b4c20e494d80b247f21a8070d3 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_1acbd565184940b397749fc75bbcfbe4.setIcon(icon_bb2d00b4c20e494d80b247f21a8070d3);
            
    
            var popup_f136484683a44f20a9d01d6f1744b2cc = L.popup({maxWidth: '300'
            
            });

            
                var html_4b572f52b87745bf9eee3ec9674e47ef = $('<div id="html_4b572f52b87745bf9eee3ec9674e47ef" style="width: 100.0%; height: 100.0%;">$394</div>')[0];
                popup_f136484683a44f20a9d01d6f1744b2cc.setContent(html_4b572f52b87745bf9eee3ec9674e47ef);
            

            marker_1acbd565184940b397749fc75bbcfbe4.bindPopup(popup_f136484683a44f20a9d01d6f1744b2cc)
            ;

            
        
    
        var marker_628051e3f3ca428eb43ac50c7edd5713 = L.marker(
            [32.877256063740894, -96.8757989788942],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_f41f22f1705f4fecb182767e26a25d67 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_628051e3f3ca428eb43ac50c7edd5713.setIcon(icon_f41f22f1705f4fecb182767e26a25d67);
            
    
            var popup_2a6d91bfb28549c7b2fc63fe9a251e61 = L.popup({maxWidth: '300'
            
            });

            
                var html_11c845a54dd847e4ae631bc207bb952a = $('<div id="html_11c845a54dd847e4ae631bc207bb952a" style="width: 100.0%; height: 100.0%;">$85</div>')[0];
                popup_2a6d91bfb28549c7b2fc63fe9a251e61.setContent(html_11c845a54dd847e4ae631bc207bb952a);
            

            marker_628051e3f3ca428eb43ac50c7edd5713.bindPopup(popup_2a6d91bfb28549c7b2fc63fe9a251e61)
            ;

            
        
    
        var marker_bfc0d4a532ac4783a22920275cc8c5e9 = L.marker(
            [32.8981462981182, -96.8586509057892],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_aef20a38710241ea988a177789820ead = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_bfc0d4a532ac4783a22920275cc8c5e9.setIcon(icon_aef20a38710241ea988a177789820ead);
            
    
            var popup_75b9b5e5270a4aa2aa4269df5c8c203a = L.popup({maxWidth: '300'
            
            });

            
                var html_be57efb4163547eeb80c611caf2dc41e = $('<div id="html_be57efb4163547eeb80c611caf2dc41e" style="width: 100.0%; height: 100.0%;">$80</div>')[0];
                popup_75b9b5e5270a4aa2aa4269df5c8c203a.setContent(html_be57efb4163547eeb80c611caf2dc41e);
            

            marker_bfc0d4a532ac4783a22920275cc8c5e9.bindPopup(popup_75b9b5e5270a4aa2aa4269df5c8c203a)
            ;

            
        
    
        var marker_84c2a9b188ba4ed3837965110485a92f = L.marker(
            [32.9040282448911, -96.86996727735821],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_5f1d6fa7951c4786bf3c639c4864fa2a = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_84c2a9b188ba4ed3837965110485a92f.setIcon(icon_5f1d6fa7951c4786bf3c639c4864fa2a);
            
    
            var popup_d7e9e9b8de1440a9a3267f6d02c9cb02 = L.popup({maxWidth: '300'
            
            });

            
                var html_af39a5d451f7411785a9b01a8d451d9b = $('<div id="html_af39a5d451f7411785a9b01a8d451d9b" style="width: 100.0%; height: 100.0%;">$50</div>')[0];
                popup_d7e9e9b8de1440a9a3267f6d02c9cb02.setContent(html_af39a5d451f7411785a9b01a8d451d9b);
            

            marker_84c2a9b188ba4ed3837965110485a92f.bindPopup(popup_d7e9e9b8de1440a9a3267f6d02c9cb02)
            ;

            
        
    
        var marker_ca2a7b672598490d909554d31dcc9e1a = L.marker(
            [32.8771344812899, -96.86328393723329],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_2691848d15944eac82fd72e52c7c7b65 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'purple',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_ca2a7b672598490d909554d31dcc9e1a.setIcon(icon_2691848d15944eac82fd72e52c7c7b65);
            
    
            var popup_35166f223df647629698b1d174b4bd8e = L.popup({maxWidth: '300'
            
            });

            
                var html_ff194c00fe774f64b8630bf22798abd0 = $('<div id="html_ff194c00fe774f64b8630bf22798abd0" style="width: 100.0%; height: 100.0%;">$165</div>')[0];
                popup_35166f223df647629698b1d174b4bd8e.setContent(html_ff194c00fe774f64b8630bf22798abd0);
            

            marker_ca2a7b672598490d909554d31dcc9e1a.bindPopup(popup_35166f223df647629698b1d174b4bd8e)
            ;

            
        
    
        var marker_835e88ab57444db891827f857c1a0618 = L.marker(
            [32.8920481255171, -96.8717408122603],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_e1c52f388dcf4870a52b33a9fe365378 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_835e88ab57444db891827f857c1a0618.setIcon(icon_e1c52f388dcf4870a52b33a9fe365378);
            
    
            var popup_c5c90441cf3941959dbb476c9bafa566 = L.popup({maxWidth: '300'
            
            });

            
                var html_c5b46896ebeb4178a5c5f1eff2d9e929 = $('<div id="html_c5b46896ebeb4178a5c5f1eff2d9e929" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_c5c90441cf3941959dbb476c9bafa566.setContent(html_c5b46896ebeb4178a5c5f1eff2d9e929);
            

            marker_835e88ab57444db891827f857c1a0618.bindPopup(popup_c5c90441cf3941959dbb476c9bafa566)
            ;

            
        
    
        var marker_03d6fd34cc5a4eb3b115bb61981d9a22 = L.marker(
            [32.892048, -96.871741],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_91eae633d9cc416696e5804b5a3bad3a = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'black',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_03d6fd34cc5a4eb3b115bb61981d9a22.setIcon(icon_91eae633d9cc416696e5804b5a3bad3a);
            
    
            var popup_da1c24703e9746f68d5e470e4986c9c9 = L.popup({maxWidth: '300'
            
            });

            
                var html_b1baf228f0924f45b4873086144a7232 = $('<div id="html_b1baf228f0924f45b4873086144a7232" style="width: 100.0%; height: 100.0%;">Location</div>')[0];
                popup_da1c24703e9746f68d5e470e4986c9c9.setContent(html_b1baf228f0924f45b4873086144a7232);
            

            marker_03d6fd34cc5a4eb3b115bb61981d9a22.bindPopup(popup_da1c24703e9746f68d5e470e4986c9c9)
            ;

            
        
    

            var circle_5a4f0bb5140d416db4e20df7a7187f94 = L.circle(
                [32.892048, -96.871741],
                {
  "bubblingMouseEvents": true,
  "color": "#696969",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "#ff0000",
  "fillOpacity": 0.05,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 2000,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
            
    
        var marker_c0f0beebc44040fc98a2a571192f6361 = L.marker(
            [32.8933181190263, -96.8618881394887],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_0fe7eb77fb6848dea45488c6c1bb9b04 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_c0f0beebc44040fc98a2a571192f6361.setIcon(icon_0fe7eb77fb6848dea45488c6c1bb9b04);
            
    
            var popup_ef4c2464b64d436fabc3da8f3a898295 = L.popup({maxWidth: '300'
            
            });

            
                var html_6e87152f90d749a29359d369a098093c = $('<div id="html_6e87152f90d749a29359d369a098093c" style="width: 100.0%; height: 100.0%;">$33</div>')[0];
                popup_ef4c2464b64d436fabc3da8f3a898295.setContent(html_6e87152f90d749a29359d369a098093c);
            

            marker_c0f0beebc44040fc98a2a571192f6361.bindPopup(popup_ef4c2464b64d436fabc3da8f3a898295)
            ;

            
        
    
        var marker_4904a43d6d4e458f98ae68d01d41e5e9 = L.marker(
            [32.8949295039901, -96.86206701896309],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_f5eb6405f1e841cfa40b11828f40273c = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_4904a43d6d4e458f98ae68d01d41e5e9.setIcon(icon_f5eb6405f1e841cfa40b11828f40273c);
            
    
            var popup_84c759cad3d54e48a1c6d8a7e0f56ad5 = L.popup({maxWidth: '300'
            
            });

            
                var html_841f247e83ff4acfb3230debad6d7a49 = $('<div id="html_841f247e83ff4acfb3230debad6d7a49" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_84c759cad3d54e48a1c6d8a7e0f56ad5.setContent(html_841f247e83ff4acfb3230debad6d7a49);
            

            marker_4904a43d6d4e458f98ae68d01d41e5e9.bindPopup(popup_84c759cad3d54e48a1c6d8a7e0f56ad5)
            ;

            
        
    
        var marker_edecbfc02ec84f48b3c3865254e52a2c = L.marker(
            [32.8820233239255, -96.87511098155849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_0cfe094088214ab08d69eb02cc4569ed = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_edecbfc02ec84f48b3c3865254e52a2c.setIcon(icon_0cfe094088214ab08d69eb02cc4569ed);
            
    
            var popup_a9397274132642fc89903cc551b852e1 = L.popup({maxWidth: '300'
            
            });

            
                var html_4e30193cc41e40399ffc62cc5f2a4461 = $('<div id="html_4e30193cc41e40399ffc62cc5f2a4461" style="width: 100.0%; height: 100.0%;">$1000</div>')[0];
                popup_a9397274132642fc89903cc551b852e1.setContent(html_4e30193cc41e40399ffc62cc5f2a4461);
            

            marker_edecbfc02ec84f48b3c3865254e52a2c.bindPopup(popup_a9397274132642fc89903cc551b852e1)
            ;

            
        
    
        var marker_82d75b3ee4aa48ba9910fc7fc3b6f9ca = L.marker(
            [32.9077810249579, -96.8621826243898],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_5dca4a97d0624dcf9c702efb27f9ed6b = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_82d75b3ee4aa48ba9910fc7fc3b6f9ca.setIcon(icon_5dca4a97d0624dcf9c702efb27f9ed6b);
            
    
            var popup_774250c31f9a4e819f62ed65a8e4fca7 = L.popup({maxWidth: '300'
            
            });

            
                var html_c4e787626af043d6930b2583dafae188 = $('<div id="html_c4e787626af043d6930b2583dafae188" style="width: 100.0%; height: 100.0%;">$369</div>')[0];
                popup_774250c31f9a4e819f62ed65a8e4fca7.setContent(html_c4e787626af043d6930b2583dafae188);
            

            marker_82d75b3ee4aa48ba9910fc7fc3b6f9ca.bindPopup(popup_774250c31f9a4e819f62ed65a8e4fca7)
            ;

            
        
    
        var marker_fc446ce0d6ba414797505eae793b7c00 = L.marker(
            [32.8944793226889, -96.85326030618401],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_62e1f872f2a940bebe3a3347f8d7ab2f = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_fc446ce0d6ba414797505eae793b7c00.setIcon(icon_62e1f872f2a940bebe3a3347f8d7ab2f);
            
    
            var popup_adce4b1cc1774c67a94824147eff34ee = L.popup({maxWidth: '300'
            
            });

            
                var html_90def270e1db4869b553d7cc2663e7db = $('<div id="html_90def270e1db4869b553d7cc2663e7db" style="width: 100.0%; height: 100.0%;">$49</div>')[0];
                popup_adce4b1cc1774c67a94824147eff34ee.setContent(html_90def270e1db4869b553d7cc2663e7db);
            

            marker_fc446ce0d6ba414797505eae793b7c00.bindPopup(popup_adce4b1cc1774c67a94824147eff34ee)
            ;

            
        
    
        var marker_45b75e64935f497697fbf87628605814 = L.marker(
            [32.8969128016987, -96.8695319039417],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_6a82552bd3f34138a4904ae8b2badc24 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_45b75e64935f497697fbf87628605814.setIcon(icon_6a82552bd3f34138a4904ae8b2badc24);
            
    
            var popup_93eb9156e23a46d9887fc3b9ad71acd1 = L.popup({maxWidth: '300'
            
            });

            
                var html_4d1ba9a23cfb43e2841aa78f50cf5e95 = $('<div id="html_4d1ba9a23cfb43e2841aa78f50cf5e95" style="width: 100.0%; height: 100.0%;">$40</div>')[0];
                popup_93eb9156e23a46d9887fc3b9ad71acd1.setContent(html_4d1ba9a23cfb43e2841aa78f50cf5e95);
            

            marker_45b75e64935f497697fbf87628605814.bindPopup(popup_93eb9156e23a46d9887fc3b9ad71acd1)
            ;

            
        
    
        var marker_10a56ec49530436ab93c678ca3e2f91e = L.marker(
            [32.901805911191104, -96.86800149482849],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_564be1c2263c4e5b8991b22f211ed89b = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_10a56ec49530436ab93c678ca3e2f91e.setIcon(icon_564be1c2263c4e5b8991b22f211ed89b);
            
    
            var popup_8249ba8e79554c5dab4345d56a5a4503 = L.popup({maxWidth: '300'
            
            });

            
                var html_207de026bb614e8bb6a4219a907d1c0d = $('<div id="html_207de026bb614e8bb6a4219a907d1c0d" style="width: 100.0%; height: 100.0%;">$67</div>')[0];
                popup_8249ba8e79554c5dab4345d56a5a4503.setContent(html_207de026bb614e8bb6a4219a907d1c0d);
            

            marker_10a56ec49530436ab93c678ca3e2f91e.bindPopup(popup_8249ba8e79554c5dab4345d56a5a4503)
            ;

            
        
    
        var marker_8aa03188a60245019484107defa12df0 = L.marker(
            [32.9031087655529, -96.8667337476207],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_7addc7cf1a5742cf91d48d478cef1e1c = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_8aa03188a60245019484107defa12df0.setIcon(icon_7addc7cf1a5742cf91d48d478cef1e1c);
            
    
            var popup_f1c6cc650d5b4820a049b606209d5f0b = L.popup({maxWidth: '300'
            
            });

            
                var html_2307938f791146c6ae1656065f4ad4a5 = $('<div id="html_2307938f791146c6ae1656065f4ad4a5" style="width: 100.0%; height: 100.0%;">$95</div>')[0];
                popup_f1c6cc650d5b4820a049b606209d5f0b.setContent(html_2307938f791146c6ae1656065f4ad4a5);
            

            marker_8aa03188a60245019484107defa12df0.bindPopup(popup_f1c6cc650d5b4820a049b606209d5f0b)
            ;

            
        
    
        var marker_d5a560302b0043059f415540b71302b8 = L.marker(
            [32.8852465509118, -96.87014674082121],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_fe3a71cd077d434197e55d2a37f29d51 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_d5a560302b0043059f415540b71302b8.setIcon(icon_fe3a71cd077d434197e55d2a37f29d51);
            
    
            var popup_94e499d6dc884b1a8735d65c161c8c6d = L.popup({maxWidth: '300'
            
            });

            
                var html_33a16421a2fe4953abd034ab0ac8f209 = $('<div id="html_33a16421a2fe4953abd034ab0ac8f209" style="width: 100.0%; height: 100.0%;">$75</div>')[0];
                popup_94e499d6dc884b1a8735d65c161c8c6d.setContent(html_33a16421a2fe4953abd034ab0ac8f209);
            

            marker_d5a560302b0043059f415540b71302b8.bindPopup(popup_94e499d6dc884b1a8735d65c161c8c6d)
            ;

            
        
    
        var marker_e2a50066fd814d57aaab6ba5eda93abb = L.marker(
            [32.883227682540806, -96.86105138861559],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_1a1f7102d7dd46e2a22c30a2671ca0b6 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'pink',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_e2a50066fd814d57aaab6ba5eda93abb.setIcon(icon_1a1f7102d7dd46e2a22c30a2671ca0b6);
            
    
            var popup_9e971eaafe4549d4a66d23c39db1ec8b = L.popup({maxWidth: '300'
            
            });

            
                var html_90a57cb43d354c88beaa02b79ebad4de = $('<div id="html_90a57cb43d354c88beaa02b79ebad4de" style="width: 100.0%; height: 100.0%;">$394</div>')[0];
                popup_9e971eaafe4549d4a66d23c39db1ec8b.setContent(html_90a57cb43d354c88beaa02b79ebad4de);
            

            marker_e2a50066fd814d57aaab6ba5eda93abb.bindPopup(popup_9e971eaafe4549d4a66d23c39db1ec8b)
            ;

            
        
    
        var marker_a690bce441454e7b92d8ab8b236a56e5 = L.marker(
            [32.877256063740894, -96.8757989788942],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_8f40c6988f1442fc8ed3ab76b38013ff = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_a690bce441454e7b92d8ab8b236a56e5.setIcon(icon_8f40c6988f1442fc8ed3ab76b38013ff);
            
    
            var popup_dbecb018c5f14ffaaff386f7a990502a = L.popup({maxWidth: '300'
            
            });

            
                var html_6374e061c7ea4a6bb592b64a7e942da4 = $('<div id="html_6374e061c7ea4a6bb592b64a7e942da4" style="width: 100.0%; height: 100.0%;">$85</div>')[0];
                popup_dbecb018c5f14ffaaff386f7a990502a.setContent(html_6374e061c7ea4a6bb592b64a7e942da4);
            

            marker_a690bce441454e7b92d8ab8b236a56e5.bindPopup(popup_dbecb018c5f14ffaaff386f7a990502a)
            ;

            
        
    
        var marker_70685698085046ebbcb973f221143731 = L.marker(
            [32.8981462981182, -96.8586509057892],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_f564adcadfd24573ac46f5a1e77441c4 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'blue',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_70685698085046ebbcb973f221143731.setIcon(icon_f564adcadfd24573ac46f5a1e77441c4);
            
    
            var popup_9bb854f964dd44f39788e6803d051149 = L.popup({maxWidth: '300'
            
            });

            
                var html_1d448518b41842fd8386bd690b9ed36a = $('<div id="html_1d448518b41842fd8386bd690b9ed36a" style="width: 100.0%; height: 100.0%;">$80</div>')[0];
                popup_9bb854f964dd44f39788e6803d051149.setContent(html_1d448518b41842fd8386bd690b9ed36a);
            

            marker_70685698085046ebbcb973f221143731.bindPopup(popup_9bb854f964dd44f39788e6803d051149)
            ;

            
        
    
        var marker_0cf04faa89564c469b79fc3421148e30 = L.marker(
            [32.9040282448911, -96.86996727735821],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_3fe92917cb1948c6988f297fda52b005 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_0cf04faa89564c469b79fc3421148e30.setIcon(icon_3fe92917cb1948c6988f297fda52b005);
            
    
            var popup_85f0c5cbdeb54aae8fd17702cc24c545 = L.popup({maxWidth: '300'
            
            });

            
                var html_08d4630ee8284ba589f4b15290e3a4a5 = $('<div id="html_08d4630ee8284ba589f4b15290e3a4a5" style="width: 100.0%; height: 100.0%;">$50</div>')[0];
                popup_85f0c5cbdeb54aae8fd17702cc24c545.setContent(html_08d4630ee8284ba589f4b15290e3a4a5);
            

            marker_0cf04faa89564c469b79fc3421148e30.bindPopup(popup_85f0c5cbdeb54aae8fd17702cc24c545)
            ;

            
        
    
        var marker_924a2dee63674848b0b5764ae7d73f86 = L.marker(
            [32.8771344812899, -96.86328393723329],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_cf95405b79624ab0b7cf842eb57e3ea4 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'purple',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_924a2dee63674848b0b5764ae7d73f86.setIcon(icon_cf95405b79624ab0b7cf842eb57e3ea4);
            
    
            var popup_544a8e54e8cf4badbd0f351ac872be4f = L.popup({maxWidth: '300'
            
            });

            
                var html_0a03fe6738aa45528931acaf2c9a3539 = $('<div id="html_0a03fe6738aa45528931acaf2c9a3539" style="width: 100.0%; height: 100.0%;">$165</div>')[0];
                popup_544a8e54e8cf4badbd0f351ac872be4f.setContent(html_0a03fe6738aa45528931acaf2c9a3539);
            

            marker_924a2dee63674848b0b5764ae7d73f86.bindPopup(popup_544a8e54e8cf4badbd0f351ac872be4f)
            ;

            
        
    
        var marker_2f0e32c10ffa417e8433570a0291954c = L.marker(
            [32.8920481255171, -96.8717408122603],
            {
                icon: new L.Icon.Default()
                }
            ).addTo(map_35b429a7a5304ceeaa87803d67a0cd86);
        
    

                var icon_c65999dafec3484a96bebebb9faa9278 = L.AwesomeMarkers.icon({
                    icon: 'home',
                    iconColor: 'white',
                    markerColor: 'red',
                    prefix: 'glyphicon',
                    extraClasses: 'fa-rotate-0'
                    });
                marker_2f0e32c10ffa417e8433570a0291954c.setIcon(icon_c65999dafec3484a96bebebb9faa9278);
            
    
            var popup_4b7ae2c717ab401c8a86ba5c4ae7a937 = L.popup({maxWidth: '300'
            
            });

            
                var html_d5d404fdeed94217879b2cdfd4e8a741 = $('<div id="html_d5d404fdeed94217879b2cdfd4e8a741" style="width: 100.0%; height: 100.0%;">$37</div>')[0];
                popup_4b7ae2c717ab401c8a86ba5c4ae7a937.setContent(html_d5d404fdeed94217879b2cdfd4e8a741);
            

            marker_2f0e32c10ffa417e8433570a0291954c.bindPopup(popup_4b7ae2c717ab401c8a86ba5c4ae7a937)
            ;

            
        
</script>

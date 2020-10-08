
let currentDate = new Date(),
    oceania1 = document.getElementById("oceania-1"),
    oceania2 = document.getElementById("oceania-2"),
    oceania3 = document.getElementById("oceania-3"),
    europa = document.getElementById("europa"),
    europeTime = 0,
    america1 = document.getElementById("america-1"),
    america2 = document.getElementById("america-2"),
    america3 = document.getElementById("america-3"),
    america4 = document.getElementById("america-4"),
    americaTime = 0,
    brasilTime = 0;




if (1601121960000 < currentDate && currentDate < 1617447960000) {
    oceania1.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +14)</span>
                                <img src="/imagen/banderas/kiribati.jpg" alt="Kiribati">
                                <img src="/imagen/banderas/samoa.jpg" alt="Samoa">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_1">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_1">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_1">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_1">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>KIRIBATI</span>
                                        <img src="/imagen/banderas/kiribati.jpg" alt="Kiribati">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Catholic Church Christmas, London</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">1.987149,-157.477137</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>SAMOA</span>
                                        <img src="/imagen/banderas/samoa.jpg" alt="Samoa">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Fagali'i, Apia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-13.831357,-171.766401</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    oceania2.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +13)</span>
                                <img src="/imagen/banderas/nueva-zelanda.jpg" alt="Nueva Zelanda">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_2">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_2">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_2">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_2">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>NUEVA ZELANDA</span>
                                        <img src="/imagen/banderas/nueva-zelanda.jpg" alt="Nueva Zelanda">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Wellington Botanic Garden, Wellington</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-41.282491,174.769132</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Auckland Town, Auckland</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-36.843391,174.767093</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Christchurch Botanic Gardens, Christchurch</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-43.530635,172.621909</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +12)</span>
                                <img src="/imagen/banderas/fiyi.jpg" alt="Fiyi">
                                <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_3">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_3">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_3">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_3">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>FIYI</span>
                                        <img src="/imagen/banderas/fiyi.jpg" alt="Fiyi">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Albert Park, Suva</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-18.146580,178.424547</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>My Suva Picnic Park, Suva</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-18.155665,178.446365</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>RUSIA</span>
                                        <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Petropavlovsk-Kamchatskiy, Kamchatka Krai</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">53.021702,158.646749</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
} 

if (1601755200000 < currentDate && currentDate < 1617447960000) {
    oceania3.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +11)</span>
                                <img src="/imagen/banderas/australia.jpg" alt="Australia">
                                <img src="/imagen/banderas/vanuatu.jpg" alt="Vanuatu">
                                <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_4">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_4">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_4">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_4">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>AUSTRALIA</span>
                                        <img src="/imagen/banderas/australia.jpg" alt="Australia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Royal Botanic Gardens, Sidney</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.863021,151.215353</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Queen Victoria Gardens, Melbourne</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-37.821492,144.971232</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>City Botanic Gardens, Brisbane</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-27.476013,153.029658</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Hobart, Tasmania</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-42.881375,147.329955</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>VANUATU</span>
                                        <img src="/imagen/banderas/vanuatu.jpg" alt="Vanuatu">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Independence Park, Port Vila</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-17.738237,168.313621</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>RUSIA</span>
                                        <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Magadán, Óblast de Magadán</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">59.560179,150.803796</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +10:30)</span>
                                <img src="/imagen/banderas/australia.jpg" alt="Australia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_6">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_6">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_6">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_6">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>AUSTRALIA</span>
                                        <img src="/imagen/banderas/australia.jpg" alt="Australia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Adelaide Botanic Garden, Adelaide</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.918194,138.611379</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +10)</span>
                                <img src="/imagen/banderas/guam.jpg" alt="Guam">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_5">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_5">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_5">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_5">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GUAM</span>
                                        <img src="/imagen/banderas/guam.jpg" alt="Guam">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Tumon Bay, Tamuning</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">13.513504,144.805744</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    horaadelaide = "10";
} else {
    horaadelaide = "09";
}

if (1604167200000 < currentDate && currentDate < 1610816400000) {
    oceania2.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +13)</span>
                                <img src="/imagen/banderas/nueva-zelanda.jpg" alt="Nueva Zelanda">
                                <img src="/imagen/banderas/fiyi.jpg" alt="Fiyi">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_2">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_2">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_2">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_2">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>NUEVA ZELANDA</span>
                                        <img src="/imagen/banderas/nueva-zelanda.jpg" alt="Nueva Zelanda">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Wellington Botanic Garden, Wellington</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-41.282491,174.769132</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Auckland Town, Auckland</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-36.843391,174.767093</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Christchurch Botanic Gardens, Christchurch</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-43.530635,172.621909</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="map_country">
                                    <div class="flag">
                                        <span>FIYI</span>
                                        <img src="/imagen/banderas/fiyi.jpg" alt="Fiyi">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Albert Park, Suva</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-18.146580,178.424547</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>My Suva Picnic Park, Suva</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-18.155665,178.446365</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +12)</span>
                                <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_3">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_3">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_3">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_3">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>RUSIA</span>
                                        <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Petropavlovsk-Kamchatskiy, Kamchatka Krai</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">53.021702,158.646749</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
}

if (1603598400000 < currentDate && currentDate < 1616907600000) {
    europa.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +03)</span>
                                <img src="/imagen/banderas/turquia.jpg" alt="Turquia">
                                <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_14">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_14">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_14">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_14">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>TURQUÍA</span>
                                        <img src="/imagen/banderas/turquia.jpg" alt="Turquia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Kültürpark İzmir, Esmirna</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.427560,27.145376</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Büyükpark, Esmirna</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.462685,27.216880</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Gulhane Parki, Estambul</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">41.011949,28.978977</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Botanic Bahcesi, Gaziantep</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">37.061963,37.351613</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>RUSIA</span>
                                        <img src="/imagen/banderas/rusia.jpg" alt="Rusia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Kitay-Gorod, Moscú</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">55.752945,37.613809</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +02)</span>
                                <img src="/imagen/banderas/grecia.jpg" alt="Grecia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_40">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_40">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_40">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_40">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GRECIA</span>
                                        <img src="/imagen/banderas/grecia.jpg" alt="Grecia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Jardín Nacional de Atenas, Athenas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">37.972660,23.737270</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>YMCA Park, Salónica</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.626361,22.952033</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +01)</span>
                                <img src="/imagen/banderas/hungria.jpg" alt="Hungria">
                                <img src="/imagen/banderas/españa.jpg" alt="España">
                                <img src="/imagen/banderas/francia.jpg" alt="Francia">
                                <img src="/imagen/banderas/alemania.jpg" alt="Alemania">
                                <img src="/imagen/banderas/italia.jpg" alt="Italia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_15">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_15">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_15">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_15">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>TURQUÍA</span>
                                        <img src="/imagen/banderas/hungria.jpg" alt="Hungria">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Margaret Island, Budapest</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">47.529875,19.051542</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESPAÑA</span>
                                        <img src="/imagen/banderas/españa.jpg" alt="España">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque de María Luisa, Sevilla</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">37.377148,-5.987055</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque de la Química, Zaragoza</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">41.661545,-0.894701</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque de El Retiro, Madrid</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.417543,-3.682446</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Urbano Abelardo Sánchez, Albacete</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.985585,-1.858075</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque de la Ciudadela, Barcelona</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">41.388245,2.186891</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>FRANCIA</span>
                                        <img src="/imagen/banderas/francia.jpg" alt="Francia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Westfield Les 4 Temps, Puteaux</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">48.892036,2.237655</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Tuileries Garden, Paris</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">48.863598,2.327481</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ALEMANIA</span>
                                        <img src="/imagen/banderas/alemania.jpg" alt="Alemania">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Tiergarten, Berlin</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">52.516103,13.361087</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ITALIA</span>
                                        <img src="/imagen/banderas/italia.jpg" alt="Italia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Cannaregio, Venecia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.439321,12.339091</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>San Giovanni, Florencia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">43.769561,11.255811</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Santa Croce, Venecia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.440161,12.326911</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Borgo Du Tillot, Parma</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">44.800694,10.329110</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT +00)</span>
                                <img src="/imagen/banderas/gran-bretaña.jpg" alt="Gran Bretaña">
                                <img src="/imagen/banderas/portugal.jpg" alt="Portugal">
                                <img src="/imagen/banderas/irlanda.jpg" alt="Irlanda">
                                <img src="/imagen/banderas/islandia.jpg" alt="Islandia">
                                <img src="/imagen/banderas/gran-canaria.jpg" alt="Gran Canaria">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_16">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_16">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_16">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_16">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GRAN BRETAÑA</span>
                                        <img src="/imagen/banderas/gran-bretaña.jpg" alt="Gran Bretaña">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>St. James's Park, Londres</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">51.501222,-0.139702</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>PORTUGAL</span>
                                        <img src="/imagen/banderas/portugal.jpg" alt="Portugal">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Jardín del Príncipe Real, Lisboa</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.716183,-9.148742</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>IRLANDA</span>
                                        <img src="/imagen/banderas/irlanda.jpg" alt="Irlanda">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Saint Stephen's Green, Dublin</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">53.337790,-6.259001</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ISLANDIA</span>
                                        <img src="/imagen/banderas/islandia.jpg" alt="Islandia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Miðborg, Reikiavik</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">64.127690,-21.941980</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GRAN CANARIA</span>
                                        <img src="/imagen/banderas/gran-canaria.jpg" alt="Gran Canaria">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Plaza de la Música, Las Palmas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">28.128783,-15.451647</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque del Estadio Insular, Las Palmas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">28.128741,-15.433331</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>San Cristóbal de La Laguna, Santa Cruz de Tenerife</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">28.489334,-16.317490</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -01)</span>
                                <img src="/imagen/banderas/portugal.jpg" alt="Portugal">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_17">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_17">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_17">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_17">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>PORTUGAL</span>
                                        <img src="/imagen/banderas/portugal.jpg" alt="Portugal">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Distrito de Ponta Delgada, Azores</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">37.741546,-25.668131</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    europeTime = 1;
}

if ((1599386400000 < currentDate && currentDate < 1604224800000) || (1615197600000 <= currentDate && currentDate < 1617530400000)) {
    america2.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -02:30)</span>
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_19">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_19">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_19">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_19">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Downtown, Terranova y Labrador</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">47.564991,-52.707432</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -03)</span>
                                <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_20">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_20">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_20">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_20">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>BRASIL</span>
                                        <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Ibirapuera, Sao Paulo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.550162,-46.655413</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Centro, Indaial - Santa Catarina</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-26.893355,-49.230638</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Farroupilha, Porto Alegre</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-30.036925,-51.216308</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Montes Claros, Minas Gerais</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-16.761098,-43.866721</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Federal University of Maranhão, São Luís</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.556042,-44.308388</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Palmas, Tocantins</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-10.209455,-48.324099</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Recreio dos Bandeirantes, Río de Janeiro</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.032933,-43.485812</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Natal, Río Grande del Norte</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-5.838914,-35.199559</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ARGENTINA</span>
                                        <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Rivadavia, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.617777,-58.432851</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de las Armas Ejército Argentino, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.610111,-58.368732</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CHILE</span>
                                        <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Forestal, Santiago de Chile</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.435701,-70.640991</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Olmué, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.995444,-71.185523</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Quillota, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.879444,-71.247924</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Viña del Mar, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.028076,-71.554301</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas, Punta Arenas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-53.163831,-70.899061</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>URUGUAY</span>
                                        <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque José Enrique Rodó, Montevideo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.913694,-56.165400</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Halifax, Nueva Escocia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">44.642443,-63.580160</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -04)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_21">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_21">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_21">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_21">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Central Park, Nueva York</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.765723,-73.973038</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Bryant Park, Nueva York</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.753869,-73.983796</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Northwest Washington, Washington DC</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.890812,-77.030033</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Miami, Florida</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">25.761117,-80.193901</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Disneyworld, Florida</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">28.415972,-81.580934</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Olímpico del Centenario, Atlanta</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">33.760393,-84.393414</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Campus Martius Park, Detroit</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">42.331691,-83.046502</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>High Park, Toronto</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">43.649552,-79.465872</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Golden Triangle, Ottawa</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.420927,-75.690556</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Ville-Marie, Monteal</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.502794,-73.554270</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>REPÚBLICA DOMINICANA</span>
                                        <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Centro Olimpico, Santo Domingo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">18.476709,-69.915483</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
}

if ((1603620000000 < currentDate && currentDate < 1604224800000) || (1615197600000 <= currentDate && currentDate < 1617530400000)) {
    america3.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -05)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/peru.jpg" alt="Peru">
                                <img src="/imagen/banderas/ecuador.jpg" alt="Ecuador">
                                <img src="/imagen/banderas/colombia.jpg" alt="Colombia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_22">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_22">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_22">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_22">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Muelle de la Armada, Chicago</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">41.891882,-87.598955</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Chickasaw Bricktown Ballpark, Oklahoma</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">35.465201,-97.507469</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Dallas Downtown Historic District, Dallas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">32.776721,-96.799042</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Austin, Texas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">30.274223,-97.740733</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Houston, Texas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">29.760385,-95.369804</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Downtown, Winnipeg</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">49.887753,-97.129913</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>PERÚ</span>
                                        <img src="/imagen/banderas/peru.jpg" alt="Peru">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque de la Exposición, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.062746,-77.036275</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>C.C Mega Plaza, Independencia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.994232,-77.063427</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas de Chancay, Chancay</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.563121,-77.270121</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas de Chosica, Chosica</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.933472,-76.693406</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Villa El Salvador, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.232091,-76.931591</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Universidad Nacional Mayor de San Marcos, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.053035,-77.081881</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ECUADOR</span>
                                        <img src="/imagen/banderas/ecuador.jpg" alt="Ecuador">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Samanes, Guayaquil</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.103466,-79.907960</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Jardín Botánico de Quito, Quito</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-0.185014,-78.485145</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque de la Madre, Cuenca</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.904343,-79.003210</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>COLOMBIA</span>
                                        <img src="/imagen/banderas/colombia.jpg" alt="Colombia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Itagüi, Antioquia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">6.148842,-75.618401</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -06)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/mexico.jpg" alt="Mexico">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_23">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_23">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_23">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_23">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Albuquerque, Nuevo México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">35.085182,-106.649917</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Denver, Colorado</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">39.739215,-104.990295</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Victoria Park, Regina</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">50.447895,-104.612321</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Louise McKinney Riverfront Park, Edmonton</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">53.543033,-113.488838</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>MÉXICO</span>
                                        <img src="/imagen/banderas/mexico.jpg" alt="Mexico">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Alameda Central, Ciudad de México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">19.435731,-99.143961</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Hundido, Ciudad de México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">19.378292,-99.178743</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Poza Rica de Hidalgo, Veracruz</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">20.532138,-97.459704</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>;`
}

if (1604224800000 <= currentDate && currentDate < 1615197600000) {
    america1.innerHTML = ``;
    america2.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -03)</span>
                                <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                <img src="/imagen/banderas/groelandia.jpg" alt="Groenlandia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_20">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_20">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_20">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_20">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>BRASIL</span>
                                        <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Ibirapuera, Sao Paulo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.584210,-46.659413</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Centro, Indaial - Santa Catarina</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-26.893355,-49.230638</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Farroupilha, Porto Alegre</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-30.036925,-51.216308</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Montes Claros, Minas Gerais</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-16.761098,-43.866721</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Federal University of Maranhão, São Luís</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.556042,-44.308388</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Palmas, Tocantins</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-10.209455,-48.324099</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Recreio dos Bandeirantes, Río de Janeiro</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.032933,-43.485812</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Natal, Río Grande del Norte</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-5.838914,-35.199559</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ARGENTINA</span>
                                        <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Rivadavia, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.617777,-58.432851</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de las Armas Ejército Argentino, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.610111,-58.368732</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CHILE</span>
                                        <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Forestal, Santiago de Chile</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.435701,-70.640991</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Olmué, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.995444,-71.185523</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Quillota, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.879444,-71.247924</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Viña del Mar, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.028076,-71.554301</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas, Punta Arenas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-53.163831,-70.899061</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>URUGUAY</span>
                                        <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque José Enrique Rodó, Montevideo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.913694,-56.165400</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GROENLANDIA</span>
                                        <img src="/imagen/banderas/groelandia.jpg" alt="Groenlandia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Tuujuk, Nuuk</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">64.174190,-51.738516</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -03:30)</span>
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_19">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_19">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_19">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_19">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Downtown, Terranova y Labrador</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">47.564991,-52.707432</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -04)</span>
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_21">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_21">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_21">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_21">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Halifax, Nueva Escocia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">44.642443,-63.580160</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>REPÚBLICA DOMINICANA</span>
                                        <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Centro Olimpico, Santo Domingo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">18.476709,-69.915483</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    america3.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -05)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/peru.jpg" alt="Peru">
                                <img src="/imagen/banderas/ecuador.jpg" alt="Ecuador">
                                <img src="/imagen/banderas/colombia.jpg" alt="Colombia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_22">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_22">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_22">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_22">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Central Park, Nueva York</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.765723,-73.973038</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Bryant Park, Nueva York</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">40.753869,-73.983796</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Northwest Washington, Washington DC</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">38.890812,-77.030033</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Miami, Florida</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">25.761117,-80.193901</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Disneyworld, Florida</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">28.415972,-81.580934</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Olímpico del Centenario, Atlanta</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">33.760393,-84.393414</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Campus Martius Park, Detroit</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">42.331691,-83.046502</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>High Park, Toronto</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">43.649552,-79.465872</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Golden Triangle, Ottawa</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.420927,-75.690556</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Ville-Marie, Monteal</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">45.502794,-73.554270</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>PERÚ</span>
                                        <img src="/imagen/banderas/peru.jpg" alt="Peru">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque de la Exposición, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.062746,-77.036275</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>C.C Mega Plaza, Independencia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.994232,-77.063427</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas de Chancay, Chancay</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.563121,-77.270121</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas de Chosica, Chosica</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-11.933472,-76.693406</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Villa El Salvador, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.232091,-76.931591</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Universidad Nacional Mayor de San Marcos, Lima</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-12.053035,-77.081881</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ECUADOR</span>
                                        <img src="/imagen/banderas/ecuador.jpg" alt="Ecuador">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Samanes, Guayaquil</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.103466,-79.907960</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Jardín Botánico de Quito, Quito</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-0.185014,-78.485145</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque de la Madre, Cuenca</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.904343,-79.003210</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>COLOMBIA</span>
                                        <img src="/imagen/banderas/colombia.jpg" alt="Colombia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Itagüi, Antioquia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">6.148842,-75.618401</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -06)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/mexico.jpg" alt="Mexico">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_23">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_23">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_23">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_23">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Muelle de la Armada, Chicago</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">41.891882,-87.598955</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Chickasaw Bricktown Ballpark, Oklahoma</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">35.465201,-97.507469</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Dallas Downtown Historic District, Dallas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">32.776721,-96.799042</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Austin, Texas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">30.274223,-97.740733</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Houston, Texas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">29.760385,-95.369804</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Victoria Park, Regina</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">50.447895,-104.612321</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Downtown, Winnipeg</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">49.887753,-97.129913</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>MÉXICO</span>
                                        <img src="/imagen/banderas/mexico.jpg" alt="Mexico">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Alameda Central, Ciudad de México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">19.435731,-99.143961</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Hundido, Ciudad de México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">19.378292,-99.178743</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Poza Rica de Hidalgo, Veracruz</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">20.532138,-97.459704</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;                 
    america4.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -07)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_41">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_41">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_41">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_41">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estados Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Albuquerque, Nuevo México</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">35.085182,-106.649917</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Denver, Colorado</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">39.739215,-104.990295</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Louise McKinney Riverfront Park, Edmonton</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">53.543033,-113.488838</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -08)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_24">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_24">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_24">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_24">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Pier39, San Francisco</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">37.808971,-122.410242</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Santa Monica Pier, Santa Monica</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">34.010113,-118.495742</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Paradise, Las Vegas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">36.115972,-115.174323</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Waterfront, Long Beach</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">33.761667,-118.197294</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>T-Mobile Park, Seattle</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">47.591324,-122.333023</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Queen Elizabeth Park, Vancouver</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">49.240966,-123.112591</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -09)</span>
                                <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_25">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_25">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_25">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_25">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ESTADOS UNIDOS</span>
                                        <img src="/imagen/banderas/usa.jpg" alt="Estado Unidos">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Downtown, Anchorage</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">61.216691,-149.892453</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    americaTime = 1;
}
    
if (1604224800000 <= currentDate && currentDate < 1613458800000) {
    america1.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -02)</span>
                                <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_18">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_18">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_18">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_18">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>BRASIL</span>
                                        <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Ibirapuera, Sao Paulo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.584210,-46.659413</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;
    america2.innerHTML = `<div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -03)</span>
                                <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                <img src="/imagen/banderas/groelandia.jpg" alt="Groenlandia">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_20">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_20">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_20">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_20">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>BRASIL</span>
                                        <img src="/imagen/banderas/brasil.jpg" alt="Brasil">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Centro, Indaial - Santa Catarina</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-26.893355,-49.230638</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Parque Farroupilha, Porto Alegre</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-30.036925,-51.216308</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Montes Claros, Minas Gerais</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-16.761098,-43.866721</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Federal University of Maranhão, São Luís</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-2.556042,-44.308388</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Palmas, Tocantins</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-10.209455,-48.324099</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Recreio dos Bandeirantes, Río de Janeiro</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-23.032933,-43.485812</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Natal, Río Grande del Norte</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-5.838914,-35.199559</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>ARGENTINA</span>
                                        <img src="/imagen/banderas/argentina.jpg" alt="Argentina">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Rivadavia, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.617777,-58.432851</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de las Armas Ejército Argentino, Buenos Aires</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.610111,-58.368732</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CHILE</span>
                                        <img src="/imagen/banderas/chile.jpg" alt="Chile">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque Forestal, Santiago de Chile</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.435701,-70.640991</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Olmué, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.995444,-71.185523</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Quillota, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-32.879444,-71.247924</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Viña del Mar, Valparaíso</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-33.028076,-71.554301</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                        <div class="city">
                                            <span>Plaza de Armas, Punta Arenas</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-53.163831,-70.899061</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>URUGUAY</span>
                                        <img src="/imagen/banderas/uruguay.jpg" alt="Uruguay">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Parque José Enrique Rodó, Montevideo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">-34.913694,-56.165400</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>GROENLANDIA</span>
                                        <img src="/imagen/banderas/groelandia.jpg" alt="Groenlandia">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Tuujuk, Nuuk</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">64.174190,-51.738516</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -03:30)</span>
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_19">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_19">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_19">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_19">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Downtown, Terranova y Labrador</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">47.564991,-52.707432</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="zone">
                            <div class="zone_gmt">
                                <span>(GMT -04)</span>
                                <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                            </div>
                            <div class="zone_time">
                                <div class="localtime">
                                    <div class="local">
                                        <span>Hora local de este lugar:</span>
                                        <div id="localTime_21">Obteniendo datos...</div>
                                    </div>
                                    <button class="button">Ver CC</button>
                                </div>
                                <div class="startend">
                                    <div class="start">
                                        <span>Inicio:</span>
                                        <div id="timeStart_21">Obteniendo datos...</div>
                                    </div>
                                    <div class="end">
                                        <span>Fin:</span>
                                        <div id="timeEnd_21">Obteniendo datos...</div>
                                    </div>
                                </div>
                                <div class="countdown" id="countdown_21">
                                    Obteniendo datos...
                                </div>
                            </div>
                            <div class="map">
                                <div class="map_country">
                                    <div class="flag">
                                        <span>CANADÁ</span>
                                        <img src="/imagen/banderas/canada.jpg" alt="Canada">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Halifax, Nueva Escocia</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">44.642443,-63.580160</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="map_country">
                                    <div class="flag">
                                        <span>REPÚBLICA DOMINICANA</span>
                                        <img src="/imagen/banderas/republica_dominicana.jpg" alt="Republica Dominicana">
                                    </div>
                                    <div>
                                        <div class="city">
                                            <span>Centro Olimpico, Santo Domingo</span>
                                        </div>
                                        <div class="coordes">
                                            <p class="cc">18.476709,-69.915483</p>
                                            <div class="copy">Copiar</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>`;        
    brasilTime = 1;
}



//variables
let copy = [...document.getElementsByClassName('copy')],
cc = [...document.getElementsByClassName('cc')],
coordes = document.getElementById('coordes'),
button = [...document.getElementsByClassName('button')],
map = [...document.getElementsByClassName('map')];


//for para agregar el data-index a un grupo de elementos.   
for (let index = 0; index < button.length; index++) {
button[index].setAttribute('data-index',index);
}

//array de numero a dias
const dia = (e) => {
let day = ['Dom','Lun','Mar','Mie','Jue','Vie','Sab'];
return day[e];
}
//array de numero a meses
const mes = (e) => {
let mes = ['Ene','Feb','Mar','Abr','May','Jun','Jul','Ago','Set','Oct','Nov','Dic'];
return mes[e];
}
//formato 00:00:00
const time = (e) =>{
let timeFormat = ('0' + e).slice(-2);
return timeFormat;
}


//funcion que devuelve un objetos de los tiempos
const tiempo = (tiempoFormat) => {
let ahora = new Date(),
remaintime = (new Date(tiempoFormat) - ahora + 1000)/1000,
remainsecond = ('0' + Math.floor(remaintime % 60)).slice(-2),
remaiminutes = ('0' + Math.floor(remaintime / 60 % 60)).slice(-2),
remaihours = ('0' + Math.floor(remaintime / 3600 % 24)).slice(-2),
remaidays = Math.floor(remaintime / (3600 * 24));
return{
    remaintime,
    remainsecond,
    remainsecond,
    remaiminutes,
    remaihours,
    remaidays
}
}

//funcion copiar texto
const copyText = (e) => {
    window.getSelection().removeAllRanges();
let range = document.createRange();
range.selectNode(e.target.previousElementSibling);
window.getSelection().addRange(range);
document.execCommand('copy');
window.getSelection().removeAllRanges();
}

//funcion boton CC
const openClose = (index) => {
let Close = map[index].style.display;
if (Close == 'block') {
    map[index].style.display = 'none';
    button[index].innerHTML ='Ver CC';
    button[index].style.backgroundColor ='transparent';
    button[index].style.color ='black';
    button[index].style.border ='1px solid black';
} else {
    map[index].style.display = 'block';
    button[index].innerHTML ='Cerrar';
    button[index].style.backgroundColor ='rgb(165, 58, 58)';
    button[index].style.color ='white';
    button[index].style.border ='1px solid rgb(165, 58, 58)';
} 
}

//Verificador de eventos
let eventHandler = e => {
const className = e.target.className;
switch (className) {
    case ('copy'):
        copyText(e);
        break;
    case ('button'):
        openClose(e.target.dataset.index);
        break;
    default:
        break;
}
}


const currentTime = (offset, id) => {
const el = document.getElementById(id);
setInterval(() => {
    let d = new Date(),
    utc = d.getTime() + (d.getTimezoneOffset() * 60000),
    nd = new Date(utc + (3600000*offset));
    el.innerHTML = `${dia(nd.getDay())}, 
                    ${nd.getDate()} de 
                    ${mes(nd.getMonth())} - 
                    ${time(nd.getHours())}:${time(nd.getMinutes())}`;
}, 1000);
}

const contador = (timeFormatStart,timeFormatEnd,timeStart,timeEnd,countDown,messageInit,messageEnd,message) => {
const dateStart = new Date(timeFormatStart),
    dateEnd = new Date(timeFormatEnd),
    start = document.getElementById(timeStart),
    end = document.getElementById(timeEnd),
    countdown = document.getElementById(countDown);

start.innerHTML = `${dia(dateStart.getDay())}, 
                    ${dateStart.getDate()} de
                    ${mes(dateStart.getMonth())} - 
                    ${time(dateStart.getHours())}:${time(dateStart.getMinutes())}`;

end.innerHTML = `${dia(dateEnd.getDay())}, 
                    ${dateEnd.getDate()} de
                    ${mes(dateEnd.getMonth())} -  
                    ${time(dateEnd.getHours())}:${time(dateEnd.getMinutes())}`;

const timerupdate = setInterval(() => {
    let t = tiempo(timeFormatStart);
    if (t.remaintime > 1) {
        countdown.innerHTML = `${messageInit} en: 
                        <span>${t.remaidays}</span><span>d</span>
                        <span>${t.remaihours}</span><span>h</span>
                        <span>${t.remaiminutes}</span><span>m</span>
                        <span>${t.remainsecond}</span><span>s</span>`;
    } else {
        let a = tiempo(timeFormatEnd);
        if (a.remaintime > 1) {
            countdown.innerHTML = `${messageEnd} en: 
                            <span>${a.remaidays}</span><span>d</span>
                            <span>${a.remaihours}</span><span>h</span>
                            <span>${a.remaiminutes}</span><span>m</span>
                            <span>${a.remainsecond}</span><span>s</span>`;
        } else {
            clearInterval(timerupdate);
            countdown.innerHTML = `${message}`;
        }
    }
}, 1000);            
}
const startHour = 11,
    endHour = startHour + 6,
    //startDay = "Sat Aug 8 2020",
    //endDay = "Sat Aug 8 2020",
    messStart = "Comienza",
    messEnd = "Termina",
    messFinal = "EVENTO FINALIZADO";

contador(`${startDay} ${startHour}:00:00 GMT+1400`,`${endDay} ${endHour}:00:00 GMT+1400`,"timeStart_1","timeEnd_1","countdown_1",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+1300`,`${endDay} ${endHour}:00:00 GMT+1300`,"timeStart_2","timeEnd_2","countdown_2",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+1200`,`${endDay} ${endHour}:00:00 GMT+1200`,"timeStart_3","timeEnd_3","countdown_3",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+1100`,`${endDay} ${endHour}:00:00 GMT+1100`,"timeStart_4","timeEnd_4","countdown_4",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+1000`,`${endDay} ${endHour}:00:00 GMT+1000`,"timeStart_5","timeEnd_5","countdown_5",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+${horaadelaide}30`,`${endDay} ${endHour}:00:00 GMT+${horaadelaide}30`,"timeStart_6","timeEnd_6","countdown_6",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0900`,`${endDay} ${endHour}:00:00 GMT+0900`,"timeStart_7","timeEnd_7","countdown_7",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0800`,`${endDay} ${endHour}:00:00 GMT+0800`,"timeStart_8","timeEnd_8","countdown_8",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0700`,`${endDay} ${endHour}:00:00 GMT+0700`,"timeStart_9","timeEnd_9","countdown_9",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0600`,`${endDay} ${endHour}:00:00 GMT+0600`,"timeStart_10","timeEnd_10","countdown_10",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0530`,`${endDay} ${endHour}:00:00 GMT+0530`,"timeStart_11","timeEnd_11","countdown_11",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0500`,`${endDay} ${endHour}:00:00 GMT+0500`,"timeStart_12","timeEnd_12","countdown_12",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0400`,`${endDay} ${endHour}:00:00 GMT+0400`,"timeStart_13","timeEnd_13","countdown_13",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT+0300`,`${endDay} ${endHour}:00:00 GMT+0300`,"timeStart_14","timeEnd_14","countdown_14",messStart, messEnd, messFinal);

if (europeTime == 1) {
    contador(`${startDay} ${startHour}:00:00 GMT+0100`,`${endDay} ${endHour}:00:00 GMT+0100`,"timeStart_15","timeEnd_15","countdown_15",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT+0000`,`${endDay} ${endHour}:00:00 GMT+0000`,"timeStart_16","timeEnd_16","countdown_16",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0100`,`${endDay} ${endHour}:00:00 GMT-0100`,"timeStart_17","timeEnd_17","countdown_17",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT+0200`,`${endDay} ${endHour}:00:00 GMT+0200`,"timeStart_40","timeEnd_40","countdown_40",messStart, messEnd, messFinal);
    currentTime(+01,"localTime_15");
    currentTime(+00,"localTime_16");
    currentTime(-01,"localTime_17");
    currentTime(+02,"localTime_40");
} else {
    contador(`${startDay} ${startHour}:00:00 GMT+0200`,`${endDay} ${endHour}:00:00 GMT+0200`,"timeStart_15","timeEnd_15","countdown_15",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT+0100`,`${endDay} ${endHour}:00:00 GMT+0100`,"timeStart_16","timeEnd_16","countdown_16",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT+0000`,`${endDay} ${endHour}:00:00 GMT+0000`,"timeStart_17","timeEnd_17","countdown_17",messStart, messEnd, messFinal);
    currentTime(+02,"localTime_15");
    currentTime(+01,"localTime_16");
    currentTime(+00,"localTime_17");
}

if (brasilTime == 1) {
    contador(`${startDay} ${startHour}:00:00 GMT-0200`,`${endDay} ${endHour}:00:00 GMT-0200`,"timeStart_18","timeEnd_18","countdown_18",messStart, messEnd, messFinal);
    currentTime(-02,"localTime_18");
}

if (americaTime == 1) {
    contador(`${startDay} ${startHour}:00:00 GMT-0330`,`${endDay} ${endHour}:00:00 GMT-0330`,"timeStart_19","timeEnd_19","countdown_19",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0800`,`${endDay} ${endHour}:00:00 GMT-0800`,"timeStart_24","timeEnd_24","countdown_24",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0900`,`${endDay} ${endHour}:00:00 GMT-0900`,"timeStart_25","timeEnd_25","countdown_25",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0700`,`${endDay} ${endHour}:00:00 GMT-0700`,"timeStart_41","timeEnd_41","countdown_41",messStart, messEnd, messFinal);
    currentTime(-3.5,"localTime_19");
    currentTime(-08,"localTime_24");
    currentTime(-09,"localTime_25");
    currentTime(-07,"localTime_41");
    
} else {
    contador(`${startDay} ${startHour}:00:00 GMT-0200`,`${endDay} ${endHour}:00:00 GMT-0200`,"timeStart_18","timeEnd_18","countdown_18",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0230`,`${endDay} ${endHour}:00:00 GMT-0230`,"timeStart_19","timeEnd_19","countdown_19",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0700`,`${endDay} ${endHour}:00:00 GMT-0700`,"timeStart_24","timeEnd_24","countdown_24",messStart, messEnd, messFinal);
    contador(`${startDay} ${startHour}:00:00 GMT-0800`,`${endDay} ${endHour}:00:00 GMT-0800`,"timeStart_25","timeEnd_25","countdown_25",messStart, messEnd, messFinal);
    currentTime(-02,"localTime_18");
    currentTime(-2.5,"localTime_19");
    currentTime(-07,"localTime_24");
    currentTime(-08,"localTime_25");
}



contador(`${startDay} ${startHour}:00:00 GMT-0300`,`${endDay} ${endHour}:00:00 GMT-0300`,"timeStart_20","timeEnd_20","countdown_20",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT-0400`,`${endDay} ${endHour}:00:00 GMT-0400`,"timeStart_21","timeEnd_21","countdown_21",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT-0500`,`${endDay} ${endHour}:00:00 GMT-0500`,"timeStart_22","timeEnd_22","countdown_22",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT-0600`,`${endDay} ${endHour}:00:00 GMT-0600`,"timeStart_23","timeEnd_23","countdown_23",messStart, messEnd, messFinal);

contador(`${startDay} ${startHour}:00:00 GMT-1000`,`${endDay} ${endHour}:00:00 GMT-1000`,"timeStart_26","timeEnd_26","countdown_26",messStart, messEnd, messFinal);
contador(`${startDay} ${startHour}:00:00 GMT-1100`,`${endDay} ${endHour}:00:00 GMT-1100`,"timeStart_27","timeEnd_27","countdown_27",messStart, messEnd, messFinal);

currentTime(+14,"localTime_1");
currentTime(+13,"localTime_2");
currentTime(+12,"localTime_3");
currentTime(+11,"localTime_4");
currentTime(+10,"localTime_5");
currentTime(`+${horaadelaide}.5`,"localTime_6");
currentTime(+09,"localTime_7");
currentTime(+08,"localTime_8");
currentTime(+07,"localTime_9");
currentTime(+06,"localTime_10");
currentTime(+5.5,"localTime_11");
currentTime(+05,"localTime_12");
currentTime(+04,"localTime_13");
currentTime(+03,"localTime_14");

currentTime(-03,"localTime_20");
currentTime(-04,"localTime_21");
currentTime(-05,"localTime_22");
currentTime(-06,"localTime_23");

currentTime(-10,"localTime_26");
currentTime(-11,"localTime_27");

coordes.addEventListener('click',eventHandler);


let timeLocal = document.getElementById('time_local');

const local_day_hour = () => {
    let gmtNum = "";
    let dateLocalGMT = new Date(); 
    let gmt = (-1)*dateLocalGMT.getTimezoneOffset()/60;
    let gmtRes = (-1)*dateLocalGMT.getTimezoneOffset()%60;
    if (gmtRes == 0) {
        if (gmt > 0) {
            gmtNum = `+${gmt}`;
        } else if (gmt < 0) {
            gmtNum = `${gmt}`;
        } else {
            gmtNum = "+00";
        }
    } else if (gmtRes == 30 || gmtRes == -30) {
        if (gmt > 0) {
            gmtNum = `+${gmt.toString().slice(0,-2)}:30`;
        } else if (gmt < 0) {
            gmtNum = `${gmt.toString().slice(0,-2)}:30`;
        }
    } else if (gmtRes == 45 || gmtRes == -45) {
        if (gmt > 0) {
            gmtNum = `+${gmt.toString().slice(0,-3)}:45`;
        } else if (gmt < 0) {
            gmtNum = `${gmt.toString().slice(0,-3)}:45`;
        }
    }
    setInterval(() => {
        let dateLocal = new Date(); 
        timeLocal.innerHTML = `<p>
                                    ${dia(dateLocal.getDay())}, 
                                    ${dateLocal.getDate()}  
                                    ${mes(dateLocal.getMonth())}. del 
                                    ${dateLocal.getFullYear()}
                                </p>
                                <p>
                                    ${time(dateLocal.getHours())}:${time(dateLocal.getMinutes())}:${time(dateLocal.getSeconds())} GMT${gmtNum}
                                </p>`;
    }, 1000);   
}
local_day_hour();

window.onload = function () {
    let loader = document.getElementById('onload');
    loader.setAttribute('class','loader active');
}



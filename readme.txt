        
		//////////////////////////////////////////////////////////////
		// MET CE CODE EN HAUT ENTRE LE <HEAD> </HEAD> DU CLIENT.PHP//
		//////////////////////////////////////////////////////////////
		
		// met ton lien perso pour: hotel.bootstrap.css
		
		<link rel="stylesheet" type="text/css" href="nistype/hotel.bootstrap.css">
		<script src="https://kit.fontawesome.com/0ec861ef00.js" crossorigin="anonymous"></script>
	    <script src="<?= PATH; ?>/assets/js/client/jquery.min.js" charset="utf-8"></script>
		
		
		///////////////////////////////////////////
		// ce code en bas de page avant </body> //
		//                              </html>//
		/////////////////////////////////////////
		
		// met ton lien perso pour: hotel.bootstrap.js
		
		<div class="client__buttons">
            <button data-toggle="modal" data-target="#myModal" class="client__close"> 
		        <i class="client__close__icon icon icon--habbo"></i>
		        <div class="client__close__expand" style="width: 0px;"></div>
		    </button>
            <button id="open_full_screen" class="client__fullscreen">
		        <i class="client__fullscreen__icon icon icon--fullscreen"></i> 
		        <i class="client__fullscreen__icon icon icon--fullscreen-back ng-hide"></i>
		    </button>
			
			<button id="open_notif_client" class="client__fullscreen"><i class="fas fa-info-circle"></i></button>
        </div>

		<div id="LoadingNotification"></div>
		
		<div class="modal fade" id="myModal" role="dialog">
		    <div class="client__buttons">
                <button data-toggle="modal" data-target="#myModal" class="client__close"> 
		            <i class="client__close__icon icon icon--habbo"></i>
		            <div class="client__close__expand" style="width: 0px;"></div>
		        </button>
            </div>
	        <div class="modal-dialog modal-full">
			    <div class="modal-content">
                    <div class="modal-body">
                        <div id="LoadingPageWeb"></div>
                    </div>
                </div>
            </div>
		</div>
        
		<script src="hotel.bootstrap.js"></script>
		<script>LoadPageSrc = "http://nistype.fr/me";</script>

Nollet Antoine Gr11 SESI

Pour ouvrir le projet, ouvrez dans un navigateur web le fichier 'index.html'


règles média-queries :
						- @media print
							S'applique lorsque l'affichage est fait sur imprimante
							(utilisé dans style_general.css)
							
						- @media (min-height: 480px), screen and (orientation: portrait)
							S'applique si l'appareil possède une hauteur supérieure ou égale à 480 pixels 
							ou si l'écran est en mode portrait
							(utilisé dans style_general.css)

Sélecteurs CSS utilisés : 	
							- :hover
								Sélectionne un élément où on place le curseur de la souris.
								( utilisé sur le footer et sur les éléments images fils direct d'un élément a, les deux dans style_general.css )
								
							- :only-of-type
								Sélectionne un élément qui est seul élément de son type.
								( utilisé dans style_general.css et dans style_document.css, tous sur un h1)
								
							- :first-of-type
								Sélectionne un élément qui est premier élément de son type.
								( utilisé dans style_general.css sur les éléments span emboîtés dans un élément nav)
								
							- :nth-of-type
								Sélectionne d'une manière pré-définie des éléments d'un même type.
								( utilisé sur des éléments h1 dans style_document.css et sur des éléments nav dans style_sommaire.css)
								
							- :not()
								Sélectionne les éléments ne coreespondants pas au critère rentré
								( utilisé sur un élément h1 dans style_document.css )
								
		
Règles utilisés :
							- text-shadow
								contrôle la nuance de l'ombre d'un texte
								(utilisé dans style_general.css)
								
							-box-shadow
								contrôle la nuance de l'ombre des bordures d'un élément
								(utilisé dans style_général.css)
								
							-display:inline
								fait afficher en ligne les éléments d'une liste
								(utilisé dans style_general.css)
								
							-transform:translateX , transform:translateY , tranform:translateX
								permet de déplacer un élément sur le plan représenté par le document. 
								Cette transformation est définie à l'aide d'un vecteur dont les coordonnées 
								définissent la quantité de déplacement sur chaque axe (horizontal et vertical).
								(utilisé dans toute les feuilles de style)
								
							-z-index
								La propriété z-index définit le « z-order » (NdT : « ordre z » 
								n'est pas usité) d'un élément positionné et de ses éléments fils
								(utilisé dans style_general.css pour le header)
								
							
							

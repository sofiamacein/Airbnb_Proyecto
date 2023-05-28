# Poyecto Machine Learnirng: Airbnb

**Descripción**:

En este proyecto se va a analizar un conjunto de datos extraído de Airbnb mediante técnicas de scraping con el fin de crear un evaluador automático de precios a partir de las características de los alojamientos.


En primer lugar, se da una descripción de las variables iniciales del conjunto de datos

**_id_**: Identificador de la entrada.

**_experiences_offered_**: Indica qué experiencias complementarias se pueden obtener con la reserva. Las observaciones toman siempre el valor 'none'.

**_host_id_**: Identificador del host (hospedador).

**_host_name_**:  Nombre del host.

**_host_since_**: Fecha desde que es host.
       
**_host_location_**: Ubicación (distrito, ciudad, estado, país...) del host.

**_host_response_time_**: Tiempo que tarda el host en responder.

**_host_response_rate_**: Porcentaje medio de respuesta del host.
       
**_host_acceptance_rate_**: Tasa de aceptación de solicitudes por parte del host. 

**_host_is_superhost_**: Indica si el host es considerado 'super host'.

**_host_neighbourhood_**: Distrito en el que vive el host.
       
**_host_listings_count_**: Número de alojamientos ofertados por el host.

**_host_total_listings_count_**: Número total de alojamientos ofertados por el host.
       
**_host_has_profile_pic_**: Indica si el host tiene foto de perfil.

**_host_identity_verified_**: Indica si la identidad del host ha sido verificada.

**_street_**: Ciudad, Provincia, País del alojamineto ofertado.

**_neighbourhood_**: Barrio en el que se encuentra el alojamiento ofertado.

**_neighbourhood_cleansed_**: Barrio en el que se encuentra el alojamiento ofertado.

**_neighbourhood_group_cleansed_**: Barrio en el que se encuentra el alojamiento ofertado.
No toma ningún valor.

**_city_**: Ciudad en la que se encunetra el alojamiento ofertado.

**_state_**: Provincia en la que se encuentra el alojamiento ofertado,

**_zipcode_**: Código postal del alojamiento ofertado.

**_market_**: 

**_smart_location_**: Ciudad, país donde se encuentra el alojamiento ofertado.

**_country_code_**: Código del país del alojamiento ofertado. En este caso, siempre es 'CA' (Canadá)

**_country_**: País en el que se encuentra el alojamiento ofertado. En este caso, siempre es 'Canada'. 

**_latitude_**: Latitud del alojamiento ofertado.

**_longitude_**: Longitud del alojamiento ofertado.

**_is_location_exact_**: Indica si la ubicación es precisa.

**_property_type_**: Tipo de alojamiento ofertado 

**_room_type_**: Tipo de habitación ofertada.

**_accommodates_**: Número máximo de huéspedes.

**_bathrooms_**: Número de baños del alojamiento ofertado.

**_bedrooms_**: Número de habitaciones del alojamiento ofertado.

**_beds_**: Número de camas del alojamiento ofertado. 

**_bed_type_**: Tipo de cama del alojamiento ofertado.

**_square_feet_**: Superficie (en pies cuarados) del alojamiento ofertado. 

**_price_**: Precio por noche del alojamiento ofertado.

**_weekly_price_**: 

'monthly_price', 

'security_deposit', 

'cleaning_fee',

'guests_included', 

'extra_people', 

'minimum_nights', 

'maximum_nights',

'minimum_minimum_nights', 

'maximum_minimum_nights',

'minimum_maximum_nights', 

'maximum_maximum_nights',

'minimum_nights_avg_ntm', 

'maximum_nights_avg_ntm', 

'calendar_updated',

'has_availability', 

'availability_30', 

'availability_60',

'availability_90', 

'availability_365', 

'calendar_last_scraped',

'number_of_reviews', 

'number_of_reviews_ltm', 

'first_review',

'last_review', 

'review_scores_rating', 

'review_scores_accuracy',

'review_scores_cleanliness', 

'review_scores_checkin',

'review_scores_communication', 

'review_scores_location',

'review_scores_value', 

'requires_license', 

'license',

'instant_bookable', 

'is_business_travel_ready', 

'cancellation_policy',

'require_guest_profile_picture', 

'require_guest_phone_verification',

'calculated_host_listings_count',

'calculated_host_listings_count_entire_homes',

'calculated_host_listings_count_private_rooms',

'calculated_host_listings_count_shared_rooms', 

'reviews_per_month'

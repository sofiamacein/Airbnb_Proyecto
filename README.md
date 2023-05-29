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

**_weekly_price_**: Precio por semana del alojamiento ofertado.

**_monthly_price_**: Precio por mes del alojamiento ofertado.

**_security_deposit_**: Fianza.

**_cleaning_fee_**: Tasa de limpieza.

**_guests_included_**: Número de invitados permitidos.

**_extra_people_**: Precio por invitado (precio por guests).

**_minimum_nights_**: Noches mínimas de alquiler del alojamiento ofertado. 

**_maximum_nights_**: Noches máximas de alquiler del alojamiento ofertado.

**_minimum_minimum_nights_**: 

**_maximum_minimum_nights_**:

**_minimum_maximum_nights_**:

**_maximum_maximum_nights_**:

**_minimum_nights_avg_ntm_** :

**_maximum_nights_avg_ntm_**:

**_calendar_updated_**: Última actualización del calendario de reservas.

**_has_availability_**: Indica si el alojamiento ofertado está disponible.

**_availability_30_**: Indica si el alojamiento ofertado está disponible en los siguientes 30 días.

**_availability_60_**: Indica si el alojamiento ofertado está disponible en los siguientes 60 días.

**_availability_90_**: Indica si el alojamiento ofertado está disponible en los siguientes 90 días.

**_availability_365_**: Indica si el alojamiento ofertado está disponible en los siguientes 365 días.

**_calendar_last_scraped_**: Última actualización de la entrada.

**_number_of_reviews_**: Número de reseñas del alojamiento ofertado

**_number_of_reviews_ltm_**:

**_first_review_**: Fecha de la primera reseña registrada.

**_last_review_**:  Fecha de la última reseña registrada.

**_review_scores_rating_**:  Puntuación global en porecentaje.

**_review_scores_accuracy_**: Puntuación global con valores del 1 al 10.

**_review_scores_cleanliness_**: Puntuación (sobre 10) de la limpieza del alojamiento ofertado.

**_review_scores_checkin_**: Puntuación (sobre 10) del checkin del alojamiento ofertado.

**_review_scores_communication_**: Puntuación (sobre 10) de la comunicación con el host del alojamiento ofertado.

**_review_scores_location_**: Puntuación (sobre 10) de la ubicación del alojamiento ofertado.

**_review_scores_value_**: Puntuación sobre 10 del alojamiento ofertado.

**_requires_license_**: Indica si el host tiene licencia de hospedaje.

**_license_**: Número de licencia del host, en caso de tenerla.

**_instant_bookable_**: Indica si es posible la reserva inmediata.

**_is_business_travel_ready_**: Indica si el alojamiento ofertado está habilitado para viajes de negocio.

**_cancellation_policy_**: Tipo de política de cancelación.

**_require_guest_profile_picture_** : Indica si es obligatorio que el huésped tenga foto de perfil.

**_require_guest_phone_verification_**: Indica si es necesaria la verificación vía móvil.

**_calculated_host_listings_count_**: Número de alojamiento ofertados por el host.

**_calculated_host_listings_count_entire_homes_**: Número de apartamentos enteros ofertados por el host.

**_calculated_host_listings_count_private_rooms_**: Número de habitaciones privadas ofertadas por el host.

**_calculated_host_listings_count_shared_rooms_**: Número de habitaciones compartidas ofertadas por el host.

**_reviews_per_month_**: Número de reseñas por mes.

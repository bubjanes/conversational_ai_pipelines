## say goodbye
* goodbye
  - utter_restart_with_button
* restart
  - action_restart
  - utter_greet

## greet + out_of_scope
* greet
  - utter_greet
* out_of_scope
  - utter_out_of_scope

## restart
* restart
  - utter_restart_with_button
  - restart
  - utter_greet

## bot challenge
* ask_bot_challenge
  - utter_ask_bot_challenge

## how are you doing
* ask_howdoing
  - utter_ask_howdoing

## how old
* ask_howold
  - utter_ask_howold

## where are you from
* ask_wherefrom
  - utter_ask_wherefrom

## ask languages
* ask_languagesbot
  - utter_ask_languagesbot

## faq kunan
* faq_kunan
  - utter_faq_kunan

## out of scope
* out_of_scope
  - utter_out_of_scope

## ask weather
* ask_weather
  - utter_ask_weather

## bot name
* ask_bot_name
  - utter_ask_bot_name

## bot ask_made
* ask_made
  - utter_ask_made
  - utter_algo_mas

## human_agent
* human_agent
  - utter_human_agent

## enojo
* ask_enojo
    - utter_ask_enojo

## sintomas
* ask_sintomas
    - utter_ask_sintomas

## goodbye
* goodbye
    - utter_restart_with_button
* restart
      - action_restart
      - utter_greet

## ask_aislamiento
* ask_aislamiento
    - action_aislamiento

## ask_aislamiento_entity
* ask_aislamiento{"localidad": "cordoba"}
    - slot{"localidad": "cordoba"}
    - action_aislamiento

## ask_aislamiento_entity
* ask_aislamiento{"pais": "cordoba"}
    - slot{"pais": "cordoba"}
    - action_aislamiento

## ask_denuncia
* ask_denuncia
    - utter_ask_denuncia

## ask_mercado
* ask_mercado
    - utter_ask_mercado

## ask_familiares
* ask_familiares
    - utter_ask_familiares

## ask_banco
* ask_banco
    - utter_ask_banco

## ask_alquiler
* ask_alquiler
    - utter_ask_alquiler

## ask_credito
* ask_credito
    - utter_ask_credito

## ask_mujeres_violencia
* ask_mujeres_violencia
    - utter_ask_mujeres_violencia

## ask_farmacia
* ask_farmacia
    - utter_ask_farmacia

## ask_telefonos
* ask_telefonos
    - action_telefonos

## ask_exceptuados
* ask_exceptuados
    - action_exceptuados

## ask_transporte
* ask_transporte
    - utter_ask_transporte

## ask_restaurantes
* ask_restaurantes
    - utter_ask_restaurantes

## ask_riesgo
* ask_riesgo
    - utter_ask_riesgo

## mascota
* ask_mascota
    - utter_ask_mascota

## rapipago
* ask_rapipago
    - utter_ask_rapipago

## correo
* ask_correo
    - utter_ask_correo

## datos
* ask_datos
    - action_data

## duration of cuarentena
* ask_fincuarentena
    - utter_ask_fincuarentena

## permiso
* ask_permisocircular
    - utter_ask_permisocircular

## prevencion methods
* ask_prevencion
    - utter_ask_prevencion

## coronavirus general definition
* ask_coronavirus
    - utter_ask_coronavirus

## barbijo
* ask_barbijo
    - utter_ask_barbijo

## ask_embarazada
* ask_embarazada
    - utter_ask_embarazada

## ask_vacuna
* ask_vacuna
    - utter_ask_vacuna

## ask_ife
* ask_ife
    - utter_ask_ife

## ask_sexo
* ask_sexo
    - utter_ask_sexo

## ask_varado
* ask_varado
    - utter_ask_varado

## ask_dentista
* ask_dentista
    - utter_ask_dentista

## ask_asintomatico
* ask_asintomatico
    - utter_ask_asintomatico

## ask_rumor
* ask_rumor
    - utter_ask_rumor

## ask_empresa
* ask_empresa
    - utter_ask_empresa

## bot_challenge_2
* greet
    - utter_greet
* ask_bot_challenge
    - utter_ask_bot_challenge
* goodbye
    - utter_restart_with_button
* restart
  - action_restart
  - utter_greet

## thanks
* thanks
  - utter_denada

## bot_challenge_2
* greet
    - utter_greet
* ask_bot_challenge
    - utter_ask_bot_challenge
* goodbye
    - utter_restart_with_button
* restart
  - action_restart
  - utter_greet
* thanks

## get_started
* get_started
  - action_get_started

## ask_escuelas
* ask_escuelas
 - utter_ask_escuelas

## ask_incubacion
* ask_incubacion
 - utter_ask_incubacion

## ask_uba
* ask_uba
 - utter_ask_uba

## ask_riesgo
* ask_riesgo
 - utter_ask_riesgo

## ask_limpiar
* ask_limpiar
 - utter_ask_limpiar

## ask_sueldos
* ask_sueldos
 - utter_ask_sueldos

## ask_ferreteria
* ask_ferreteria
 - utter_ask_ferreteria

## ask_hospital
* ask_hospital
 - utter_ask_hospital

## ask_pagar_servicios
* ask_pagar_servicios
 - utter_ask_pagar_servicios

## ask_aburrido
* ask_aburrido
 - utter_ask_aburrido

## ask_residuos
* ask_residuos
 - utter_ask_residuos

## ask_evento
* ask_evento
 - utter_ask_evento

## longer stories 01
* greet
 - utter_greet
* ask_sintomas
 - utter_ask_sintomas
* ask_ferreteria
 - utter_ask_ferreteria
* ask_barbijo
 - utter_ask_barbijo
* ask_fincuarentena
 - utter_ask_fincuarentena

## longer stories 02
* greet
 - utter_greet
* ask_datos
 - action_data
* out_of_scope
 - utter_out_of_scope
* ask_aislamiento
 - action_aislamiento
* ask_prevencion
 - utter_ask_prevencion

## story with entity extraction
* ask_datos{"localidad": "santiago del estero"}
    - slot{"localidad": "santiago del estero"}
    - action_data

## ask_test
* ask_test
    - utter_ask_test

## ask_alimento
* ask_alimento
    - utter_ask_alimento

## ask_discapacidad
* ask_discapacidad
    - utter_ask_discapacidad

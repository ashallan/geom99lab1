# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?departure_time=now&destination=place_id:ChIJbzAIDYgjWU0R2H8GboMtJ0o&mode=bicycle&origin=place_id:ChIJFcSVWCfgWE0RufdV3V5F414&waypoints=place_id:ChIJ-2v3sekhWU0RyXtlPNfHXXM&waypoints=place_id:ChIJ1egpOr8jWU0Rn8oqFhG5Sp0&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJFcSVWCfgWE0RufdV3V5F414",
         "types" : [ "airport", "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ-2v3sekhWU0RyXtlPNfHXXM",
         "types" : [ "establishment", "food", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJbzAIDYgjWU0R2H8GboMtJ0o",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 48.4764844,
               "lng" : -89.1882643
            },
            "southwest" : {
               "lat" : 48.371634,
               "lng" : -89.31117929999999
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "9.1 km",
                  "value" : 9086
               },
               "duration" : {
                  "text" : "13 mins",
                  "value" : 762
               },
               "end_address" : "712 Macdonell St, Thunder Bay, ON P7B 4A6, Canada",
               "end_location" : {
                  "lat" : 48.4168517,
                  "lng" : -89.2430179
               },
               "start_address" : "Thunder Bay International Airport (YQT), 100 Princess St, Thunder Bay, ON P7E 6S2, Canada",
               "start_location" : {
                  "lat" : 48.37325269999999,
                  "lng" : -89.3096377
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "19 m",
                        "value" : 19
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 48.3732487,
                        "lng" : -89.30990009999999
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e toward \u003cb\u003eHwy 61 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "y{ffHfhb`P?r@"
                     },
                     "start_location" : {
                        "lat" : 48.37325269999999,
                        "lng" : -89.3096377
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10 m",
                        "value" : 10
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 48.3731662,
                        "lng" : -89.30994609999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y{ffHzib`PNH"
                     },
                     "start_location" : {
                        "lat" : 48.3732487,
                        "lng" : -89.30990009999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 177
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 48.3718425,
                        "lng" : -89.31117929999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "i{ffHdjb`PHAF?N@PDJFFFzAfBdBvB"
                     },
                     "start_location" : {
                        "lat" : 48.3731662,
                        "lng" : -89.30994609999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 137
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 48.371953,
                        "lng" : -89.3097585
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eRound Blvd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_sffHzqb`PPc@Vi@c@k@_@g@CGEKCIAMAI?I@I@IPe@"
                     },
                     "start_location" : {
                        "lat" : 48.3718425,
                        "lng" : -89.31117929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 150
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 48.3732563,
                        "lng" : -89.30940029999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRound Blvd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "usffH~hb`PAAIIWQQMKEo@QCAIAYCA?M?S?c@@c@@"
                     },
                     "start_location" : {
                        "lat" : 48.371953,
                        "lng" : -89.3097585
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 272
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 48.3725502,
                        "lng" : -89.30630219999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 1st cross street onto \u003cb\u003ePrincess St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{{ffHvfb`PAgG@u@@{A@g@Fm@Vc@JQJS@AHIJKLGJG^I"
                     },
                     "start_location" : {
                        "lat" : 48.3732563,
                        "lng" : -89.30940029999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 3970
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 216
                     },
                     "end_location" : {
                        "lat" : 48.4040632,
                        "lng" : -89.28863509999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHwy 61 N\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mwffHjsa`PEWaAwEAK_@yA[eA[aAi@wAa@_Ak@cA[e@{@iAk@m@]]MMi@a@e@_@k@[]Qi@Wa@Ow@Wc@Ie@Ie@Ea@Es@CsAAaB@{D?sD@uC@MAM?iC?iD@a@@mA@uAB{@?y@?aI@A?K?qUFyA?}BC{AImBSiAQgB_@kBk@aA]}@_@iAk@gBcAcAq@ECcAw@k@e@i@g@mAkAy@_A}AkBgB_CmA}A_BuBg@o@o@w@}@kA_AmAoBiCaDcEGIaC{CuBoCu@_Aq@y@m@o@i@k@e@e@u@m@}@s@}@o@ISGIa@a@"
                     },
                     "start_location" : {
                        "lat" : 48.3725502,
                        "lng" : -89.30630219999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 km",
                        "value" : 2929
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 234
                     },
                     "end_location" : {
                        "lat" : 48.40662769999999,
                        "lng" : -89.2500709
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHarbour Expy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k|lfH~d~_PK_@CECE[SeAu@IGm@_@GGKIIOGSGUCU?Q?K@QD_@@ULmBFg@?GFi@ReCBa@@a@Bq@@}@?}@IsCEgBCy@M}EWaL_@kLIaDKqDKsCAg@KmDMcCU_FKaDAs@C{@E{AG{B_@{OcAcb@KkDEqBGaD?OAkAA_@G{CE_BEqCEqDCyG@iI?eE?aB?Y@[?oA"
                     },
                     "start_location" : {
                        "lat" : 48.4040632,
                        "lng" : -89.28863509999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 620
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 48.4122022,
                        "lng" : -89.2500491
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCarrick St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mlmfH|sv_PWA_@Ak@AUBO?iACmA@uB@kEKuGCmBAu@F{@F"
                     },
                     "start_location" : {
                        "lat" : 48.40662769999999,
                        "lng" : -89.2500709
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 361
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 48.4134049,
                        "lng" : -89.2456392
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCentral Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gonfHxsv_PoA_EeAmDs@mCK]Ki@K_ACk@?G?c@Ao@?u@Bo@"
                     },
                     "start_location" : {
                        "lat" : 48.4122022,
                        "lng" : -89.2500491
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 441
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 48.4168517,
                        "lng" : -89.2430179
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMacdonell St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wvnfHfxu_PHMSOo@a@wRkM"
                     },
                     "start_location" : {
                        "lat" : 48.4134049,
                        "lng" : -89.2456392
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "8.8 km",
                  "value" : 8806
               },
               "duration" : {
                  "text" : "14 mins",
                  "value" : 864
               },
               "end_address" : "Centennial Park, 751 Centennial Park Rd, Thunder Bay, ON P7A 7K9, Canada",
               "end_location" : {
                  "lat" : 48.4764844,
                  "lng" : -89.19007309999999
               },
               "start_address" : "712 Macdonell St, Thunder Bay, ON P7B 4A6, Canada",
               "start_location" : {
                  "lat" : 48.4168517,
                  "lng" : -89.2430179
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "62 m",
                        "value" : 62
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 48.4173566,
                        "lng" : -89.24265059999999
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eMacdonell St\u003c/b\u003e toward \u003cb\u003eSquier St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ilofHzgu_PeBiA"
                     },
                     "start_location" : {
                        "lat" : 48.4168517,
                        "lng" : -89.2430179
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 125
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 48.41731679999999,
                        "lng" : -89.2409559
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSquier St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ooofHpeu_PFqI"
                     },
                     "start_location" : {
                        "lat" : 48.4173566,
                        "lng" : -89.24265059999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1348
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 124
                     },
                     "end_location" : {
                        "lat" : 48.42824090000001,
                        "lng" : -89.2330491
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eMemorial Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "goofH~zt_Pq@i@g@]yBoAy@m@IGk@a@GCgAq@cAm@{@k@mAy@}@m@g@]c@[cCcBcAo@aDuBkAu@UOKGoAy@}@o@e@]{MgI_Ak@aAq@eAs@]WmAy@"
                     },
                     "start_location" : {
                        "lat" : 48.41731679999999,
                        "lng" : -89.2409559
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.5 km",
                        "value" : 2510
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 263
                     },
                     "end_location" : {
                        "lat" : 48.4461924,
                        "lng" : -89.21271349999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eAlgoma St S\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "osqfHpis_P_A_AoIoI}FeG}@}@eAiAyHaIs@y@cA}@_@e@yAcBeBgBaBaBwA{Aa@a@_@a@{@{@aAeAmBuB_@a@sC}CiAiAaAeAw@u@}@cAcA_AuB_CUWMKKMAA}@_AgBmBiAiA]]MSEKGM?AAIo@yCa@o@aAcB_FsHiDmFmCaE"
                     },
                     "start_location" : {
                        "lat" : 48.42824090000001,
                        "lng" : -89.2330491
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 123
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 48.4469425,
                        "lng" : -89.2139299
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMcIntyre St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ucufHljo_PWf@q@lAkA|B"
                     },
                     "start_location" : {
                        "lat" : 48.4461924,
                        "lng" : -89.21271349999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1869
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 146
                     },
                     "end_location" : {
                        "lat" : 48.4637329,
                        "lng" : -89.214854
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eShuniah St\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "khufH`ro_PoCLaERcBDoADeBBc@?uEFyCJyCHsCBiA?m@@_IJeDHcAHsFJ{CFeD@cCD]@{HPwCFoABqAD"
                     },
                     "start_location" : {
                        "lat" : 48.4469425,
                        "lng" : -89.2139299
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 403
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 48.463807,
                        "lng" : -89.2093867
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHudson Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iqxfHxwo_PIaM?kBA}BAuFAaD"
                     },
                     "start_location" : {
                        "lat" : 48.4637329,
                        "lng" : -89.214854
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1189
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : 48.4698822,
                        "lng" : -89.19695729999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eArundel St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yqxfHtun_PAiAE_AIw@AKGa@Gg@Kg@I_@KYI[Sg@Yq@KUMSU]MSMOYY[[y@u@GGiC}ByBoBcByAe@e@WWOSIMAA]k@[m@M[?AISGSQo@_@gBc@{BMq@}@{Dq@{CWkAYqAa@cBa@yBUaC"
                     },
                     "start_location" : {
                        "lat" : 48.463807,
                        "lng" : -89.2093867
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1177
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 166
                     },
                     "end_location" : {
                        "lat" : 48.4764844,
                        "lng" : -89.19007309999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCentennial Park Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wwyfH~gl_PWBmAL[?MAK?UGOGOISWQUQYUg@uBcHOa@IWUi@KSQYYY]QQKm@[wAs@EC{@g@]YOKmAgAOMk@i@USGKKKMUAAUi@ACOi@EUOm@YmAMg@Ga@E]AUCWAc@CwA?MAa@?S?]@Y@U@O?Q?O@SAKCGCGEEIGG?K?GDEFCJEHCJITEJY~@Mb@Sl@IXSd@CNA@Kr@"
                     },
                     "start_location" : {
                        "lat" : 48.4698822,
                        "lng" : -89.19695729999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "y{ffHfhb`P?r@NHPA`@FRN`E~Eh@mAcAsAISEWASBSNg@a@[]Ss@Sc@EgA@c@@AgGBqCHuAb@u@LUTUXO^IEWcAcF{@_DeAyCmAcCwAoBiAkAw@o@qA{@gAi@yAg@iASgAKgCE}G@eJ@sH@oBBmODyXF}BC{AImBSiAQgB_@kBk@_C}@qDoBiAu@oB}AwBsBwCkDuD}EuFiHyIeL_JeLwA{A{AsA{BcBQ]a@a@K_@GKyCqBSQQc@Kk@?]HgA\\gEVgDDsA@{BO{FQwGWaL_@kLUsIM{DYqHa@aKSgIuB}{@K}GY_QAk[@u@?oAWAkACe@BwCAuB@kEKcKEqBNuCmJ_AkDKi@K_ACs@AsABeBHMSOgTmNeBiAFqIyAgAyBoAy@m@u@i@oEoCwEaDgEsCmFkDoDaCaOeJaC}AcBkAmAy@_A_AoIoI}FeGcCgCmJ{JcA}@_@e@_EkEyD}D_EeEkJ_K{F_GwKkLk@q@MYAKo@yCa@o@aAcB_FsHwHoLiAtBkA|BoCLaERcBDuDHyFFsHT}EBmJLeDHcAHoKRiHFyIRgFJqADIaMAiFCwKGiCKcAOiAUgAUu@m@yA}@{Ag@i@uAqAoJoI}@}@Ya@_@m@i@iAc@yAcAcFkAmFeC}Ka@yBUaCeBPi@Aa@GOGOISWc@o@Ug@uBcHYy@a@}@QYYYo@]gE{BkC{BaA}@SWg@eA_A{DUiAGs@E{@CeB?mBBgA?_@GOOMS?MLITm@lBa@pA]~@QdA"
         },
         "summary" : "Hwy 61 N and Harbour Expy",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 

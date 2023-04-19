<template>
  <q-page-container class="bg-grey-10">
    <q-page padding>
      <div class="row q-pa-none q-ma-none">
        <div class="col-4 q-pl-none q-ma-none"><q-btn size="20px" flat round color="white" icon="arrow_back" /></div>
        <div class="col-8 q-pt-md q-pb-none q-pl-none q-pr-none text-justify " style="color: white;">Información de la
          parada</div>
      </div>
      <div class="row q-pa-none q-ml-lg q-mr-lg q-mt-none q-mb-none" style="background-color: #1f1d1d;">
        <div class="col-4 q-pl-xl"><q-btn size="20px" flat round color="orange-10" icon="place" /></div>
        <div class="col-8 q-pt-md" style="font-size: medium; color: white;">Pollo Campero Centro</div>
      </div>
      <div class="q-col-gutter-md row items-start q-mr-none q-ml-sm q-mt-sm q-mb-none">
        <div class="col-11">
          <q-img
            src="https://res.cloudinary.com/nexdu/image/upload/s--IDv8DjzX--/f_auto,fl_lossy,q_auto/v1/city/ubicacion-de-santa-ana-en-santa-ana-el-salvador.png"
            :ratio="1" style="height: 200px; max-width: 320px" align="center" />
        </div>
      </div>
      <div class="row q-pa-none q-ma-none">
        <div class="col-12 q-pt-md q-pb-none q-pl-none q-pr-none text-center " style="color: white;">Lugares cercanos:</div>
      </div>
      <div class="row q-pa-none q-ml-lg q-mr-lg q-mt-sm q-mb-none" style="background-color: #1f1d1d;">
        <div class="col-12 q-pt-md q-pl-md q-pr-sm q-pb-none" style="color: white;">Iglesia Mision Internacional, Santa Ana, Sociedad Medica, Templo Peniel MCA y Tomo Rivas</div>
      </div>
      <div class="row q-pa-none q-ma-none">
        <div class="col-12 q-pt-md q-pb-none q-pl-none q-pr-none text-center " style="color: white;">Rutas que pasan por esta parada:</div>
      </div>
      <q-list class="q-ma-md" style="background-color: #1f1d1d;">
            <div class="row justify-between items-center">
              <q-item clickable v-ripple class="col-xs-9 col-sm-10 col-md-11 items-center">
                <q-item-section side top>
                  <q-icon name="directions_bus" color="cyan-3" />
                </q-item-section>
                <q-item-section>
                  <q-item-label style="color: white">Ruta 4</q-item-label>
                  <q-item-label style="color: grey" caption lines="2"
                    >6ta calle - 9a avenida</q-item-label
                  >
                </q-item-section>
                <q-item-section side top> </q-item-section>
              </q-item>
              <q-btn
                class="col-sm-2 col-md-1"
                icon="favorite"
                color="flat"
                text-color="cyan-3"
                unelevated
              >
              </q-btn>
            </div>
            <q-separator color="grey" spaced inset />
            <div class="row justify-between items-center" style="background-color: #1f1d1d;">
              <q-item clickable v-ripple class="col-xs-9 col-sm-10 col-md-11 items-center">
                <q-item-section side top>
                  <q-icon name="directions_bus" color="cyan-3" />
                </q-item-section>
                <q-item-section>
                  <q-item-label style="color: white">Ruta 4</q-item-label>
                  <q-item-label style="color: grey" caption lines="2"
                    >6ta calle - 9a avenida</q-item-label
                  >
                </q-item-section>
                <q-item-section side top> </q-item-section>
              </q-item>
              <q-btn
                class="col-sm-2 col-md-1"
                icon="favorite"
                color="flat"
                text-color="cyan-3"
                unelevated
              >
              </q-btn>
            </div>
            <q-separator color="grey" spaced inset />
            <div class="row justify-between items-center" style="background-color: #1f1d1d;">
              <q-item clickable v-ripple class="col-xs-9 col-sm-10 col-md-11 items-center">
                <q-item-section side top>
                  <q-icon name="directions_bus" color="cyan-3" />
                </q-item-section>
                <q-item-section>
                  <q-item-label style="color: white">Ruta 4</q-item-label>
                  <q-item-label style="color: grey" caption lines="2"
                    >6ta calle - 9a avenida</q-item-label
                  >
                </q-item-section>
                <q-item-section side top> </q-item-section>
              </q-item>
              <q-btn
                class="col-sm-2 col-md-1"
                icon="favorite"
                color="flat"
                text-color="cyan-3"
                unelevated
              >
              </q-btn>
            </div>
            <q-separator color="grey" spaced inset />
            <div class="row justify-between items-center" style="background-color: #1f1d1d;">
              <q-item clickable v-ripple class="col-xs-9 col-sm-10 col-md-11 items-center">
                <q-item-section side top>
                  <q-icon name="directions_bus" color="cyan-3" />
                </q-item-section>
                <q-item-section>
                  <q-item-label style="color: white">Ruta 4</q-item-label>
                  <q-item-label style="color: grey" caption lines="2"
                    >6ta calle - 9a avenida</q-item-label
                  >
                </q-item-section>
                <q-item-section side top> </q-item-section>
              </q-item>
              <q-btn
                class="col-sm-2 col-md-1"
                icon="favorite"
                color="flat"
                text-color="cyan-3"
                unelevated
              >
              </q-btn>
            </div>
            <q-separator color="grey" spaced inset />
            <div class="row justify-between items-center q-ma-none" style="background-color: #1f1d1d;">
              <q-item clickable v-ripple class="col-xs-9 col-sm-10 col-md-11 items-center">
                <q-item-section side top>
                  <q-icon name="directions_bus" color="cyan-3" />
                </q-item-section>
                <q-item-section>
                  <q-item-label style="color: white">Ruta 4</q-item-label>
                  <q-item-label style="color: grey" caption lines="2"
                    >6ta calle - 9a avenida</q-item-label
                  >
                </q-item-section>
                <q-item-section side top> </q-item-section>
              </q-item>
              <q-btn
                class="col-sm-2 col-md-1"
                icon="favorite"
                color="flat"
                text-color="cyan-3"
                unelevated
              >
              </q-btn>
            </div>
          </q-list>
    </q-page>
  </q-page-container>
</template>

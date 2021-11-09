<template>
<div>
 <h1 class="text-center textocolor fredoka mt-5 pt-4">Crear Autómata</h1>
        <div class="row justify-content-center" >
            <div class="grafo1 col-md-3 mx-4 card cardaux">
                <div class="container-fluid mr-4">
                    <div class="row justify-content-center ml-1">

                            <div class="col-md-6 my-4"><button class="btn btn-success info textocolor">Crear AFD</button></div>
                            <div class="col-md-6 my-4"><button class="btn btn-success info textocolor">Crear AP's</button></div>

                    </div>

                </div>
                <div class="container-fluid py-4 mr-4">
                    <h3 class="mt-2">Autómata Finito Determinista (AFD)</h3>
                    <hr>
                    <div class="row text-center my-4">
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-primary">Añadir Estado</button>
                        </div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-success">Añadir Transición</button>
                        </div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-success">Modificar Estado Final</button>
                        </div>
                    </div>
                    <div class="row text-center">
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-danger">Eliminar Autómata</button>
                        </div>
                        <div class="col-md-4"></div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-warning"> Volver al Inicio</button>
                        </div>                       
                    </div>
                    <button class="btn btn-success btn-sm">Volver</button>
                    <div class="my-4">
                        <div>
                            <form>
                                <div class="form-group">
                                    <label for="id">Ingrese el id: </label>
                                    <input type="number" min="0" class="form-control">
                                </div>
                                <div class="text-center">
                                    <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                                </div>
                            </form>
                        </div>
                    </div>

                    <div class="my-3">
                        <form >
                            <div class="form-group">
                                <label>Ingrese el id del estado inicial de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese el id del estado final de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese carácter de la transición: </label>
                                <input type="text" minlength="1" class="form-control">
                            </div>

                            <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                        </form>
                    </div>
            </div>
        </div>
    </div>
     <div class="container-fluid py-4 mr-4">
                    <h3 class="mt-2">Autómatas de Pila (AP)</h3>
                    <div class="row text-center my-4">
                        <div class="col-md-6">
                            <button class="btn btn-sm btn-success">Crear AP 1</button>
                        </div>
                        <div class="col-md-6">
                            <button class="btn btn-sm btn-success">Crear AP 2</button>
                        </div>
                    </div>
                    <div class="row my-2">
                        <div class="col-md-4"></div>
                        <div class="col-md-4 text-center">
                            <button class="btn btn-sm btn-warning">Volver al Inicio</button>
                        </div>
                    </div>

                    <div class="row text-center my-4">
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-success">Añadir Estado</button>
                        </div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-success">Añadir Transición</button>
                        </div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-success">Modificar Estado Final</button>
                        </div>
                    </div>

                    <button class="btn btn-success btn-sm mt-3">Volver</button>

                    <div class="row text-center">
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-danger">Eliminar Autómata</button>
                        </div>
                        <div class="col-md-4"></div>
                        <div class="col-md-4">
                            <button class="btn btn-sm btn-warning"> Volver</button>
                        </div>                       
                    </div>

                    <div class="my-4">
                        <div>
                            <form >
                                <div class="form-group">
                                    <label for="id">Ingrese el id: </label>
                                    <input type="number" min="0" class="form-control" >
                                </div>
                                <div class="text-center">
                                    <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                                </div>
                            </form>

                            <form >
                                <div class="form-group">
                                    <label for="id">Ingrese el id: </label>
                                    <input type="number" min="0" class="form-control">
                                </div>
                                <div class="text-center">
                                    <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                                </div>
                            </form>
                        </div>
                    </div>

                    <div class="my-3">
                        <form >
                            <div class="form-group">
                                <label>Ingrese el id del estado inicial de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese el id del estado final de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese carácter de la transición: </label>
                                <input type="text" minlength="1" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Push(): </label>
                                <input type="text" minlength="1" class="form-control" placeholder="dejar vacío para epsilon">
                            </div>
                            <div class="form-group">
                                <label>Pop(): </label>
                                <input type="text" minlength="1" class="form-control" placeholder="dejar vacío para epsilon">
                            </div>

                            <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                        </form>

                        <form >
                            <div class="form-group">
                                <label>Ingrese el id del estado inicial de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese el id del estado final de la transición:</label>
                                <input type="number" min="0" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Ingrese carácter de la transición: </label>
                                <input type="text" minlength="1" class="form-control">
                            </div>
                            <div class="form-group">
                                <label>Push(): </label>
                                <input type="text" minlength="1" class="form-control" placeholder="dejar vacío para epsilon">
                            </div>
                            <div class="form-group">
                                <label>Pop(): </label>
                                <input type="text" minlength="1" class="form-control" placeholder="dejar vacío para epsilon">
                            </div>

                            <button class="btn btn-success btn-sm" type="submit">Agregar</button>
                        </form>
                    </div> 
                </div>
                <div class="grafo1 col-md-5 mx-3 card cardaux my-3">
                <hr>
                <div>

                    <h3 class="text-center fredoka my-3">Tabla de estados autómata Finito Determinista</h3>
                    <table class="table table-striped table-dark" aria-describedby="estados1">
                        <thead>
                            <tr>
                                <th scope="col">#</th>
                                <th scope="col">Estado</th>
                                <th scope="col">Final</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr >

                                <td>
                                    <div>
                                        <input type="checkbox" name="state" id="state">
                                        <label for="state">Estado Final</label>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                    <h3 class="text-center fredoka my-3">Tabla de estados autómata de Pila 1</h3>
                    <table class="table table-striped table-dark" aria-describedby="estados1">
                        <thead>
                            <tr>
                                <th scope="col">#</th>
                                <th scope="col">Estado</th>
                                <th scope="col">Final</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr >

                                <td>
                                    <div>
                                        <input type="checkbox" name="state" id="state">
                                        <label for="state">Estado Final</label>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                    <h3 class="text-center fredoka my-3">Tabla de estados autómata de Pila 2</h3>
                    <table class="table table-striped table-dark" aria-describedby="estados1">
                        <thead>
                            <tr>
                                <th scope="col">#</th>
                                <th scope="col">Estado</th>
                                <th scope="col">Final</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr >
                                <td></td>
                                <td></td>
                                <td>
                                    <div>
                                        <input type="checkbox" name="state" id="state">
                                        <label for="state">Estado Final</label>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                    <button class="btn btn-success btn-sm mb-3 text-right" type="submit">Guardar</button>
                </div>
                <div class="grafo1 col-md-8 card cardaux">
                <h3 class="text-center fredoka my-2">Representación</h3>
                <div class="row">
                    <div class="col-md-12">
                        <h4 class="text-center fredoka my-3" >Autómata Finito Determinista</h4>
                        <div id="AFD" class="mb-3" style="border:1px solid lightgray;"></div>
                    </div>

                    <div class="col-md-6">
                        <h4 class="text-center fredoka my-3">Autómata de Pila 1</h4>
                        <div  id="AP1" class="mb-3" style="border:1px solid lightgray;"></div>
                    </div>
                    <div class="col-md-6">
                        <h4 class="text-center fredoka my-3">Autómata de Pila 2</h4>
                        <div id="AP2" class="mb-3" style="border:1px solid lightgray;"></div>
                    </div>
                </div>
            </div>

            <!--REPRESENTACION AUTOMATAS-->
        </div>

        <h1 class="text-center fredoka textocolor my-4">Operaciones</h1>
        <div class="row justify-content-center">
            <div class="card cardaux4 col-md-10 rounded-top">
                <div class="btn-group justify-content-center" role="group">
                    <a href="#"><button class="btn btn-secondary">Expresión Regular</button></a>
                    <a href="#"><button class="btn btn-secondary">Concatenación de AP's</button></a>
                    <a href="#"><button class="btn btn-secondary">Unión de AP's</button></a>
                </div>
            </div>

            <!--CASO 1: EXPRESIÓN REGULAR-->
            <div class="cardaux2 col-md-10">
                <h3 class="text-center fredoka textocolor my-3">Expresión Regular</h3>
            </div>
            <div class="card cardaux3 col-md-10 rounded-bottom mb-3">
                <div class="container my-3">
                    <div class="text-center">
                        <a href="#ER"><button class="btn btn-success">Mostrar expresion regular</button></a>
                    </div>
                    <div class="my-3">
                        <h3 class="my-3">La expresión regular del AFD es: <strong> expresionRegularAFD </strong></h3>
                        <div id="ER" style="border:1px solid lightgray;"></div>
                    </div>
                </div>
            </div>

            <!--CASO 2: CONCATENACIÓN-->
            <div class="cardaux2 col-md-10">
                <h3 class="text-center fredoka textocolor my-3">Concatenación de AP'S</h3>
            </div>
            <div class="card cardaux3 col-md-10 rounded-bottom mb-3">
                <div class="container my-3">
                    <div class="text-center my-3">
                        <button class="btn btn-success">Mostrar concatenación</button>
                    </div>
                    <div id="APCONCATENADO" style="border:1px solid lightgray;"></div>
                    
                </div>
            </div>

            <!--CASO 3: UNION-->
            <div class="cardaux2 col-md-10">
                <h3 class="text-center fredoka textocolor my-3">Unión de AP's</h3>
            </div>
            <div class="card cardaux3 col-md-10 rounded-bottom mb-3">
                <div class="container my-3">
                    <div class="text-center my-3">
                        <button class="btn btn-success">Mostrar Unión</button>
                    </div>
                    <div id="APUNIDOS" style="border:1px solid lightgray;"></div>
                </div>
            </div>
            </div>
     </div>
</template>

<script>
import vis from 'vis'

export default {
    data(){
        return{
            estadosAutomataAFD:[{id: 'inicio', label: 'inicio', color:'#75616b47', final: false}],
            estadoAutomataAFD:{id: '', label: '', color: '#C25C0B', final: false},
            transicionesAutomataAFD:[],
            transicionAutomataAFD:{from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}},
            estadosAP1:[{id: 'inicio', label: 'inicio', color:'#75616b47', final: false}],
            estadoAP1:{id: '', label: '', color: '#C25C0B', final: false},
            transicionesAP1:[],
            transicionAP1:{from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}},
            
            pilaAP:{agrega:'',elimina:''},
            pila1:[],
            pila2:[],
            estadosAP2:[{id: 'inicio', label: 'inicio', color:'#75616b47', final: false}],
            estadoAP2:{id: '', label: '', color: '#C25C0B', final: false},
            transicionesAP2:[],
            transicionAP2:{from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}},
            
            expresionRegularAFD:'',
            
            estadosAutomataUnionAP:[],
            estadoAutomataUnionAP:{id: '', label: '', color: '#C25C0B', final: false},
            transicionesAutomataUnionAP:[],
            transicionAutomataUnionAP:{from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}},
            estadosAutomataConcatenacionAP:[],
            estadoAutomataConcatenacionAP:{id: '', label: '', color: '#C25C0B', final: false},
            transicionesAutomataConcatenacionAP:[],
            transicionAutomataConcatenacionAP:{from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}},
            alfabetoAFD:[],
            alfabetoAP1:[],
            alfabetoAP2:[],
            automataER:[],
            transicionesER:[],
            selected:false,
            selected2:false,
            automataCreate:false,
            option:'',
            opcion:0,
            representacion1:false,
            analizarPalabra:false,
            volverInicio:false,
            createTrans:false,
            creaEstado:false,
            showAps:false,
            apSeleccionado:0,
        }
    },
    created(){
    },
    methods:{
        selectAFD(){
            this.automataCreate=true;
            this.option=1;
        },
        selectAP(){
            this.automataCreate=true;
            this.selected=true;
            this.showAps=true;
            this.option=2;
        },
        createEstado(){
            this.creaEstado=true;
            this.selected=true;    
            this.selected2=true;  
            this.createTrans=false;
            this.drawAutomata();
        },
        createTransicion(){
            this.createTrans=true;
            this.selected=true;
            this.selected2=true;
            this.creaEstado=false;
            this.drawAutomata();
        },
        representacion(){
            this.representacion1=true;
        },
        representacionBack(){
            this.representacion1=false;
            this.drawAutomata();
        },
        back(){
            this.selected=false;
            this.createTrans=false;
            this.creaEstado=false;
            this.analizarPalabra=false;
            this.selected2=false;
        },
        backInicio(){
            this.automataCreate=false;
            this.creaEstado=false;
            this.option=0;
            this.opcion=0;
            this.selected=false;
        },
        backToAp(){
            this.selected=true;
            this.showAps=true;
        },
        createAP1(){
            this.selected=false;
            this.showAps=false;
            this.apSeleccionado=1;
        },
        createAP2(){
            this.selected=false;
            this.showAps=false;
            this.apSeleccionado=2;
        },
        mostrarOP1(){
            
            if(this.existeFinales(1)){
                this.opcion=1;
            }
            else{
                this.$swal("Para proseguir debe marcar como final a lo menos un estado del autómata AFD",{
                    className: "alertas",
                    button:'Aceptar',
                    title:"Aviso",
                    icon:"warning",
                });
                return;
            }
        },
        mostrarOP2(){
            if(this.existeFinales(2)){
                this.opcion=2;
            }
            else{
                this.$swal("Para proseguir debe marcar como final a lo menos un estado en los autómataa",{
                    className: "alertas",
                    button:'Aceptar',
                    title:"Aviso",
                    icon:"warning",
                });
                return;
            }
            
        },
         mostrarOP3(){
            if(this.existeFinales(3)){
                this.opcion=3;
            }
            else{
                this.$swal("Para proseguir debe marcar como final a lo menos un estado en los autómataa",{
                    className: "alertas",
                    button:'Aceptar',
                    title:"Aviso",
                    icon:"warning",
                });
                return;
            }
        },
        existeEstadoTransicion(estados, transicion)
        {
            var existeFrom=false;
            var existeTo= false;
            for(var i=0; i<estados.length;i++)
            {
                if(estados[i].id===transicion.from)
                {
                    existeFrom=true;
                }
                else{
                    if(estados[i].id!=transicion.from && existeFrom===true)
                    {
                        existeFrom=true;
                    }
                    else{
                        if(estados[i].id!=transicion.from && existeFrom===false)
                        {
                            existeFrom=false;
                        }
                    }
                }
            }
            for(var j=0; j<estados.length;j++)
            {
                if(estados[j].id===transicion.to)
                {
                    existeTo=true;
                }
                else{
                    if(estados[j].id!=transicion.to && existeTo===true)
                    {
                        existeTo=true;
                    }
                    else{
                        if(estados[j].id!=transicion.to && existeTo===false)
                        {
                            existeTo=false;
                        }
                    }
                }
            }
            if(existeFrom && existeTo)
            {
                return true;
            }
            else{
                return false;
            }
        },
        crearTransicion(){
            if(this.option===1)
            {
                if(this.transicionAutomataAFD.from ==='' || this.transicionAutomataAFD.to ==='')
                {
                    this.$swal("Estados no ingresados. Rellene todos los campos antes de continuar",{
                        className: "alertas",
                        button: "Aceptar",
                        title: "Aviso",
                        icon: "warning"
                    });
                    return;
                }
                for( var i =0; i<this.transicionesAutomataAFD.length; i++)
                {
                    if(this.transicionesAutomataAFD[i].from===this.transicionAutomataAFD.from && this.transicionesAutomataAFD[i].label === this.transicionAutomataAFD.label)
                    {
                        this.$swal("La transición ya existe. Ingrese otra",{
                            className: "alertas",
                            button: "Aceptar",
                            title: "Aviso",
                            icon: "warning"
                        });
                        return;
                    }
                } 
                if(!this.existeEstadoTransicion(this.estadosAutomataAFD, this.transicionAutomataAFD))
                {
                    this.$swal("Los estados ingresados no existen. Ingrese otros estados para generar la transición",{
                        className: "alertas",
                        button: "Aceptar",
                        title: "Aviso",
                        icon: "warning",
                    });
                    return;
                } 
                if(this.existeTransicionAFD(this.transicionesAutomataAFD,this.transicionAutomataAFD))
                {
                    this.$swal("La transición ya existe. Ingrese otra",{
                        className: "alertas",
                        button: "Aceptar",
                        title: "Aviso",
                        icon: "warning",
                    });
                    return;
                }
                for(var t=0; t<this.transicionesAutomataAFD.length;t++)
                {
                    if(this.transicionesAutomataAFD[t].from===this.transicionAutomataAFD.from && this.transicionesAutomataAFD[t].label!= this.transicionAutomataAFD.label && this.transicionesAutomataAFD[t].to ===this.transicionAutomataAFD.to){
                        var aux=[this.transicionesAutomataAFD[t].label, this.transicionAutomataAFD.label];
                        console.log("aux: ",aux);
                        this.transicionesAutomataAFD[t].label= aux[0]+ '+'+ aux[1];
                        
                        this.drawAutomata();
                        return;
                    }
                }
                this.addCaracterToAlfabeto();
                
                this.transicionesAutomataAFD.push(this.transicionAutomataAFD);
                this.transicionAutomataAFD={from:'',label: '',to:'',color:{color:'rgb(0,0,0)'}}; 
            }
            else{
                if(this.apSeleccionado===1)
                {
                    if(this.transicionAP1.from ==='' || this.transicionAP1.to ==='')
                    {
                        this.$swal("Estados no ingresados. Rellene todos los campos antes de continuar",{
                            className: "alertas",
                            button: "Aceptar",
                            title: "Aviso",
                            icon: "warning"
                        });
                        return;
                    }
                    for( var j =0; j<this.transicionesAP1.length; j++)
                    {
                        if(this.transicionesAP1[j].from===this.transicionAP1.from && this.transicionesAP1[j].label === this.transicionAP1.label)
                        {
                            this.$swal("La transición ya existe. Ingrese otra",{
                                className: "alertas",
                                button: "Aceptar",
                                title: "Aviso",
                                icon: "warning"
                            });
                            return;
                        }
                    }
                    if(!this.existeEstadoTransicion(this.estadosAP1, this.transicionAP1))
                    {
                        this.$swal("Los estados ingresados no existen. Ingrese otros estados para generar la transición",{
                            className: "alertas",
                            button: "Aceptar",
                            title: "Aviso",
                            icon: "warning",
                        });
                        return;
                    }
                    else{
                        
                        this.addCaracterToAlfabeto();
                        this.transicionesAP1.push(this.transicionAP1);
                        this.pilaAPs(this.pilaAP,this.pila1,this.transicionesAP1);
                        this.pilaAp={agrega:'',elimina:''};
                        this.transicionAP1={from:'',label: '',to:'',color:{color:'rgb(0,0,0)'}};
                    }
                }
                else{
                    if(this.apSeleccionado===2)
                    {
                        if(this.transicionAP2.from ==='' || this.transicionAP2.to ==='')
                        {
                            this.$swal("Estados no ingresadow. Rellene todos los campos antes de continuar",{
                                className: "alertas",
                                button: "Aceptar",
                                title: "Aviso",
                                icon: "warning"
                            });
                            return;
                        }
                        for( var k =0; k<this.transicionesAP2.length; k++)
                        {
                            if(this.transicionesAP2[k].from===this.transicionAP2.from && this.transicionesAP2[k].label === this.transicionAP2.label)
                            {
                                this.$swal("La transición ya existe. Ingrese otra",{
                                    className: "alertas",
                                    button: "Aceptar",
                                    title: "Aviso",
                                    icon: "warning"
                                });
                            }
                        }
                        if(!this.existeEstadoTransicion(this.estadosAP2, this.transicionAP2))
                        {
                            this.$swal("Los estados ingresados no existen. Ingrese otros estados para generar la transición",{
                                className: "alertas",
                                button: "Aceptar",
                                title: "Aviso",
                                icon: "warning",
                            });
                            return;
                        }
                        this.addCaracterToAlfabeto();
                        this.transicionesAP2.push(this.transicionAP2);
                        this.pilaAPs(this.pilaAP,this.pila2,this.transicionesAP2);
                        this.transicionAP2={from:'',label: '',to:'',color:{color:'rgb(0,0,0)'}};
                    }
                }
            }
            this.drawAutomata();
        },
        existeTransicionAFD(transiciones,transicion){
            var caracteres= [];
            var aux;
            for(var i=0; i< transiciones.length;i++){
                if(transiciones[i].from===transicion.from && transiciones[i].to===transicion.to)
                {
                    if(transiciones[i].label.includes('+'))
                    {
                        aux=transiciones[i].label;
                        caracteres=aux.split('+');
                        for(var j=0; j<caracteres.length;j++)
                        {
                            if(caracteres[j]===transicion.label)
                            {
                                return true;
                            }
                        }
                        return false;
                    }
                }
            }
        },
        existeFinales(opcion){
            if(opcion==1)
            {
                for(var i=0; i<this.estadosAutomataAFD.length;i++)
                {
                    if(this.estadosAutomataAFD[i].final===true)
                    {
                        return true;
                    }
                }
                return false;
            }
            else{
                var existe1=false;
                var existe2=false;
                for(var j=0; j<this.estadosAP1.length;j++)
                {
                    if(this.estadosAP1[j].final===true)
                    {
                        existe1=true;
                    }
                }
                for(var k=0; k<this.estadosAP2.length;k++)
                {
                    if(this.estadosAP2[k].final===true)
                    {
                        existe2=true;
                    }
                }
                if(existe1 && existe2)
                {
                    return true;
                }
                return false;
            }
        },
        delAndClear(){
            if(this.option===1)
            {
                this.estadosAutomataAFD=[];
                this.transicionesAutomataAFD=[];
            }
            else{
                if(this.apSeleccionado===1)
                {
                    this.estadosAP1=[];
                    this.transicionesAP2=[];
                }
                else{
                    if(this.apSeleccionado===2)
                    {
                        this.estadosAP2=[];
                        this.transicionesAP2=[];
                    }
                }
            }
            console.log("Autómata eliminado");
            this.drawAutomata();
        },
        
        simplificarAlfabeto(alfabeto){
            
            var newArr = [];
            var myObj = {};
            alfabeto.forEach(el => {      
                if (!(el in myObj)) { 
                    myObj[el] = true
                    newArr.push(el)
                }
            });
                        
            console.log(newArr);
            return newArr;
        },
        pilaAPs(pilaAP,pila,transiciones){
            if(pila.length<1){
                pila.push('P')                
                if(pilaAP.agrega==='' && pilaAP.elimina===''){
                    for(let k=0;k<transiciones.length;k++){
                        if(transiciones[k].from!='inicio'){
                            let nT=transiciones[k].label +  '|' + 'E' + '|' + 'E' 
                            console.log("nT",nT);
                            transiciones[k].label= nT;
                            nT = ''
                        }
                    }
                }
                if(pilaAP.agrega!='' && pilaAP.elimina==''){
                    for(let i=0;i<transiciones.length;i++){
                        
                        if(transiciones[i].from!='inicio'){
                            console.log("agrega: ",pilaAP.agrega);
                            console.log("transiciones ap1 label",transiciones[i].label);
                            let newT = transiciones[i].label + '|' + 'E' + '|' + pilaAP.agrega;
                            console.log("newT:",newT);
                            transiciones[i].label= newT;
                            newT = ''
                            pilaAP.agrega=''
                        }
                    }    
                }
                if(pilaAP.elimina!='' && pilaAP.agrega==''){
                    console.log("pop()", pilaAP.elimina);
                    for(let j=1;j<transiciones.length;j++){
                        console.log("transiciones ap1",transiciones[j]);
                        let newT = transiciones[j].label + '|' + pilaAP.elimina + '|' +'E'
                        console.log("newT:",newT);
                        transiciones[j].label= newT;
                        newT = '' 
                    }
                    pilaAP.elimina=''
                }
                if(pilaAP.agrega!='' && pilaAP.elimina!=''){
                    console.log("agrega: ", pilaAP.agrega, ", elimina: ", pilaAP.elimina);
                    for(let z=0;z< transiciones.length;z++){
                        if(transiciones[z].from!='inicio' && !transiciones[z].label.includes('|')){
                            let newElim = transiciones[z].label + '|' + pilaAP.elimina + '|' + pilaAP.agrega
                            console.log("newElim", newElim);
                            transiciones[z].label = newElim;
                            newElim='';
                            pilaAP.agrega=''
                            pilaAP.elimina=''               
                        }
                    }
                }
                console.log("pila",pilaAP);
                console.log("pila1",pila);
            }
            else{
                if(pilaAP.agrega==='' && pilaAP.elimina===''){
                    for(let m=0;m<transiciones.length;m++){
                        if(transiciones[m].from!='inicio' && !transiciones[m].label.includes('|')){
                            let nT1=transiciones[m].label +  '|' + 'E' + '|' + '|' + 'E' + '|' 
                            console.log("nt1",nT1);
                            transiciones[m].label= nT1;
                            nT1 = ''
                        }
                    }
                }
                if(pilaAP.agrega!='' && pilaAP.elimina==''){                   
                    for(let f=0;f<transiciones.length;f++){                        
                        if(transiciones[f].from!='inicio' && !transiciones[f].label.includes('|')){
                            console.log("agrega: ",pilaAP.agrega);
                            console.log("transiciones ap1 label",transiciones[f].label);
                            let newT1 = transiciones[f].label + '|' + 'E' + '|' + pilaAP.agrega;
                            console.log("newT1:",newT1);
                            transiciones[f].label= newT1;
                            newT1 = ''
                            pilaAP.agrega=''
                        }
                    }                    
                }
                if(pilaAP.elimina!='' && pilaAP.agrega==''){
                    console.log("pop()", pilaAP.elimina);
                    for(let d=1;d<transiciones.length;d++){
                        if(transiciones[d].from!='inicio' && !transiciones[d].label.includes('|')){
                            console.log("transiciones ap1",transiciones[d]);
                            let newT2 = transiciones[d].label + '|' + pilaAP.elimina + '|' +'E'
                            console.log("newT2:",newT2);
                            transiciones[d].label= newT2;
                            newT2 = ''                             
                            pilaAP.elimina=''
                        }
                    }
                }
                if(pilaAP.agrega!='' && pilaAP.elimina!=''){
                    console.log("Vienen llenitos");      
                    console.log("agrega: ", pilaAP.agrega, ", elimina: ", pilaAP.elimina);
                    for(let o=0;o< transiciones.length;o++){
                        if(transiciones[o].from!='inicio' && !transiciones[o].label.includes('|')){
                            console.log("entramos perrito");
                            let newElim1 = transiciones[o].label + '|' + pilaAP.elimina + '|' + pilaAP.agrega
                            console.log("newElim1", newElim1);
                            transiciones[o].label = newElim1;
                            newElim1='';
                            pilaAP.agrega=''
                            pilaAP.elimina=''                           
                        }
                    }
                }
                console.log("pila",pilaAP);
                console.log("pila1",pila);
            }
            
        },
        unionAp(){
            let Eap1=[];
            let Tap1=[];
    
            let Eap2=[];
            let Tap2=[];
            this.transicionesAutomataUnionAP=[];
            this.estadosAutomataUnionAP=[];
            
            this.copiarAutomata(this.estadosAP1,this.transicionesAP1,Eap1,Tap1);
            this.copiarAutomata(this.estadosAP2,this.transicionesAP2,Eap2,Tap2);
            Eap1.splice(0,1);
            Eap2.splice(0,1);
            Tap1.splice(0,1);
            Tap2.splice(0,1);
            console.log("eap1: ",Eap1);
            console.log("eap1: ",Tap1);
            console.log("Eap2 : ",Eap2);
            console.log("Tap2 : ",Tap2);
            this.copiarAutomata(Eap1,Tap1,this.estadosAutomataUnionAP,this.transicionesAutomataUnionAP);
            this.estadosAutomataUnionAP= this.estadosAutomataUnionAP.concat(Eap2);
            this.transicionesAutomataUnionAP= this.transicionesAutomataUnionAP.concat(Tap2);
            
            this.estadoAutomataUnionAP.id='inicio';
            this.estadoAutomataUnionAP.label='inicio';
            this.estadoAutomataUnionAP.color='#C25C0B';
            this.estadosAutomataUnionAP.push(this.estadoAutomataUnionAP);
            this.transicionAutomataUnionAP.from='inicio';
            this.transicionAutomataUnionAP.to=Eap1[0].id;
            this.transicionAutomataUnionAP.label='E|E|E';
            this.transicionesAutomataUnionAP.push(this.transicionAutomataUnionAP);
            this.transicionAutomataUnionAP={from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}}
            this.transicionAutomataUnionAP.from='inicio';
            this.transicionAutomataUnionAP.to=Eap2[0].id;
            this.transicionAutomataUnionAP.label='E|E|E';
            this.transicionesAutomataUnionAP.push(this.transicionAutomataUnionAP);
            console.log(this.transicionesAutomataUnionAP);
            console.log(this.estadosAutomataUnionAP);
            this.drawAutomata();
        },
        concatenacionAP(){
            this.estadosAutomataConcatenacionAP=[];
            this.transicionesAutomataConcatenacionAP=[];
            this.copiarAutomata(this.estadosAP1,this.transicionesAP1,this.estadosAutomataConcatenacionAP,this.transicionesAutomataConcatenacionAP);
            var eap2=[];
            var tap2=[];
            this.copiarAutomata(this.estadosAP2,this.transicionesAP2,eap2,tap2);
            eap2.splice(0,1);
            tap2.splice(0,1);
            var inicio=eap2[0].id;
            for(var i=0; i<this.estadosAutomataConcatenacionAP.length;i++)
            {
                if(this.estadosAutomataConcatenacionAP[i].final===true)
                {
                    this.transicionAutomataConcatenacionAP.from=this.estadosAutomataConcatenacionAP[i].id;
                    this.transicionAutomataConcatenacionAP.label='E|E|E';
                    this.transicionAutomataConcatenacionAP.to=inicio;
                    this.transicionAutomataConcatenacionAP.color={color:'rgb(255,0,0)'};
                    this.transicionesAutomataConcatenacionAP.push(this.transicionAutomataConcatenacionAP);
                    this.transicionAutomataConcatenacionAP={from: '', label: '', to: '', color: {color: 'rgb(0,0,0)'}};
                    this.estadosAutomataConcatenacionAP[i].final=false;
                    this.estadosAutomataConcatenacionAP[i].shape='ellipse';
                    this.estadosAutomataConcatenacionAP[i].color='#C25C0B';
                }
            }
            this.estadosAutomataConcatenacionAP=this.estadosAutomataConcatenacionAP.concat(eap2);
            this.transicionesAutomataConcatenacionAP=this.transicionesAutomataConcatenacionAP.concat(tap2);
            console.log("trans concatenacion: ",this.transicionesAutomataConcatenacionAP);
            this.drawAutomata();
        },
        // Crea Copia de Automata
    }
}
</script>

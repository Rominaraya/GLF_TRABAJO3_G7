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
                                <td>{{index}}</td>
                                <td>{{item.label}}</td>
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
                                <td>{{index}}</td>
                                <td>{{item.label}}</td>
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
                                <td>{{index}}</td>
                                <td>{{item.label}}</td>
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
                        <h3 class="my-3">La expresión regular del AFD es: <strong> {{expresionRegularAFD}} </strong></h3>
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
export default {}
</script>

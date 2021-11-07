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
            </div>
            </div>
</template>

<script>
export default {}
</script>

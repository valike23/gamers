<script>
    import BottomNav from "../components/BottomNav.svelte";
</script>

<div class="container-fluid">
    <div class="main">
        <div class="nav">
            <div class="row">
                <div class="cell">
                    <h2>Matches</h2>
                </div>
                <div class="cell">
                    <div class="row">
                        <div class="cell-2">
                            <div class="coins">
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 24 24"
                                    ><g fill="none" class="nc-icon-wrapper"
                                        ><path
                                            d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm.31-8.86c-1.77-.45-2.34-.94-2.34-1.67 0-.84.79-1.43 2.1-1.43 1.38 0 1.9.66 1.94 1.64h1.71c-.05-1.34-.87-2.57-2.49-2.97V5H10.9v1.69c-1.51.32-2.72 1.3-2.72 2.81 0 1.79 1.49 2.69 3.66 3.21 1.95.46 2.34 1.15 2.34 1.87 0 .53-.39 1.39-2.1 1.39-1.6 0-2.23-.72-2.32-1.64H8.04c.1 1.7 1.36 2.66 2.86 2.97V19h2.34v-1.67c1.52-.29 2.72-1.16 2.73-2.77-.01-2.2-1.9-2.96-3.66-3.42z"
                                            fill="#ecaa69"
                                        /></g
                                    ></svg
                                >
                            </div>
                        </div>
                        <div class="cell-1" style="margin-top; 10px">20</div>
                        <div class="cell-2">

                        </div>
                        <div class="cell-1">

                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="body">
            <div class="row">
                <div class="cell-sm-12 cell-md-6">
                    <div class="card">
                        <div class="card-content">
                            <div class="row">
                                <div class="cell-12 text-center">
                                    <p><strong>premier league</strong></p>
                                    <p>13:30</p>
                                </div>
                                <div class="cell-12">
                                    <div class="row">
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/chelsea.png" alt="">
                                        </div>
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/vs.png" alt="">
                                        </div>
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/manutd.png" alt="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
       
    </div>
    <BottomNav />
</div>

<style>
    .container-fluid {
        height: 100vh;
        overflow-y: scroll;
    }
    .coins {
        width: 30px;
        height: 30px;
    }
    .coins-content {
        padding-top: 40px;
    }
</style>

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
                                <img src="images/coin.png" alt="">
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
                                    <div class="row pl-3 pr-3">
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/chelsea.png" alt="">
                                            <div class="colored">
                                                10/3
                                            </div>
                                        </div>
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/vs.png" alt="">
                                            <div class="colored">
                                                10/3
                                            </div>
                                        </div>
                                        <div class="cell-4">
                                            <img style="height: 100px" src="images/manutd.png" alt="">
                                            <div class="colored">
                                                10/3
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row pl-3 pr-3">
                                        <div class="cell-4">

                                        </div>
                                        <div class="cell-2">

                                        </div>
                                        <div class="cell-6">
                                            <div class="row">
                                             <div class="cell-12 text-center">
                                                <strong style="font-size: 19px;"> 5</strong>
                                                <img style="height: 30px;" src="images/coin.png" alt="">
                                             </div>
                                             <div class="cell-12 text-center">
                                                <span>potential winnings</span>
                                                <input type="text" data-role="spinner" data-min-value="0" data-max-value="20">
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
    .colored {
        background-color:coral;
        border-radius: 8px;
        color: white;
        text-align: center;
        margin-top: 8px;
    }
</style>

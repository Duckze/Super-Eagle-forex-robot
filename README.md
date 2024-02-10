<div id="iphone">
        <div id="header">
            <h1>EAGLE  FOREX ROBOT</h1>
        </div>
        <div id="screen">
            <form action="/start-trading" method="POST">
                <div id="options">
                    <div class="option">
                        <label for="synthetic_index">Synthetic Indices:</label>
                        <select name="synthetic_index" id="synthetic_index">
                            <option value="R_75">Volatility 75</option>
                            <option value="R_10">Volatility 10</option>
                            <option value="R_25">Volatility 25</option>
                            <option value="R_50">Volatility 50</option>
                            <option value="R_100">Volatility 100</option>
                        </select>
                    </div>
                    <div class="option">
                        <label for="number_of_trades">Number Of Trades:</label>
                        <input type="number" id="number_of_trades" name="number_of_trades" placeholder="Enter Number of Trades">
                    </div>
                    <div class="option">
                        <label for="BROKER_API_Token">Broker API Token:</label>
                        <input type="text" id="BROKER_API_Token" name="BROKER_API_Token" placeholder="Enter your Broker API Token">
                    </div>
                    <div class="option">
                        <label for="BROKER_App_ID">Broker App ID:</label>
                        <input type="text" id="BROKER_App_ID" name="BROKER_App_ID" placeholder="Enter your Broker App ID">
                    </div>
                    <div class="option">
                        <label for="Serial_Key">Serial Key:</label>
                        <input type="text" id="Serial_Key" name="Serial_Key" placeholder="Enter the Serial Key">
                    </div>
                    <div class="option">
                        <label for="bet_amount">Bet Amount:</label>
                        <input type="number" id="bet_amount" name="bet_amount" placeholder="Enter Bet Amount">
                    </div>
                </div>
                <button id="submit-btn" type="submit">Start Trading</button>
            </form>
        </div>
    </div>

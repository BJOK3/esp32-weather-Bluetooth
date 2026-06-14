<!DOCTYPE html>
<html>
<body style="text-align:center;font-family:Arial">

<h2>Smart Hanger BLE</h2>
<style>
button {
  user-select: none;
  -webkit-user-select: none;
  -webkit-touch-callout: none;
  touch-action: none;
  -webkit-tap-highlight-color: transparent;
}
</style>

<button onclick="connect()">CONNECT</button><br><br>

<button
  onmousedown="send('OPEN_DOWN')"
  onmouseup="send('UP')"
  ontouchstart="send('OPEN_DOWN')"
  ontouchend="send('UP')">
OPEN
</button>

<button
  onmousedown="send('CLOSE_DOWN')"
  onmouseup="send('UP')"
  ontouchstart="send('CLOSE_DOWN')"
  ontouchend="send('UP')">
CLOSE
</button>


<script>
let char;

const SERVICE_UUID = "12345678-1234-1234-1234-1234567890ab";
const CHAR_UUID    = "abcd1234-1234-1234-1234-abcdef123456";

async function connect() {
  const device = await navigator.bluetooth.requestDevice({
    filters: [{ name: "SmartHanger_S3" }],
    optionalServices: [SERVICE_UUID]
  });

  const server = await device.gatt.connect();
  const service = await server.getPrimaryService(SERVICE_UUID);
  char = await service.getCharacteristic(CHAR_UUID);

  alert("Connected OK");
}

async function send(cmd) {<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Hanger Control</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; padding: 20px; }
        button {
            padding: 20px 40px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            user-select: none;
            touch-action: manipulation;
        }
        #status { color: #555; margin-top: 10px; font-weight: bold; }
    </style>
</head>
<body>

    <h2>Smart Hanger BLE</h2>
    <div id="status">狀態：未連線</div>
    <br>
    <button onclick="connect()">CONNECT</button>
    <br><br>

    <button
        onmousedown="send('OPEN_DOWN')" onmouseup="send('UP')"
        ontouchstart="send('OPEN_DOWN')" ontouchend="send('UP')">
        OPEN
    </button>

    <button
        onmousedown="send('CLOSE_DOWN')" onmouseup="send('UP')"
        ontouchstart="send('CLOSE_DOWN')" ontouchend="send('UP')">
        CLOSE
    </button>

    <script>
        let char;
        const statusDiv = document.getElementById('status');
        const SERVICE_UUID = "12345678-1234-1234-1234-1234567890ab";
        const CHAR_UUID    = "abcd1234-1234-1234-1234-abcdef123456";

        async function connect() {
            try {
                statusDiv.innerText = "連線中...";
                const device = await navigator.bluetooth.requestDevice({
                    filters: [{ name: "SmartHanger_S3" }],
                    optionalServices: [SERVICE_UUID]
                });

                const server = await device.gatt.connect();
                const service = await server.getPrimaryService(SERVICE_UUID);
                char = await service.getCharacteristic(CHAR_UUID);
                
                statusDiv.innerText = "狀態：已連線";
                alert("裝置連線成功！");
            } catch (error) {
                statusDiv.innerText = "狀態：連線失敗";
                console.error(error);
                alert("連線失敗: " + error);
            }
        }

        async function send(cmd) {
            if (!char) return alert("請先點擊 CONNECT 連線裝置");
            try {
                const data = new TextEncoder().encode(cmd);
                await char.writeValue(data);
            } catch (error) {
                console.error("發送錯誤:", error);
            }
        }
    </script>
</body>
</html>
  if (!char) return alert("Not connected");

  const data = new TextEncoder().encode(cmd);
  await char.writeValue(data);
}
</script>

</body>
</html>
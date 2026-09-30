export default {
  async fetch(request) {
    const url = new URL(request.url);
    url.hostname = '[2a06:9801:700:0:507e:3fc3:d771:54d4]';
    url.port = '443';
    url.protocol = 'https:';
    
    const headers = new Headers(request.headers);
    headers.set('Host', 'gq.manob.ir');
    
    return fetch(new Request(url, {
      method: request.method,
      headers: headers,
      body: request.body,
      redirect: 'follow'
    }));
  }
}

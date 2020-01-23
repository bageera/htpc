# bageera HTPC Setup


## Containers
- [Traefik](https://containo.us/traefik/) - cloud natibe edge router
- [Plex Media Server](https://www.plex.tv/) - for managing media and serving files to Plex Clients
- [Radarr](https://radarr.video/) - for Movie Management
- [Sonarr](https://sonarr.tv/) - for TV Series Management
- mylar
- lidar
- sabnbzd
- pihole
- nextcloud
- mariadb
- [Ombi](https://ombi.io/) - for requesting additional library content
- [Tautulli](http://tautulli.com/) - for Plex library statistics and usage
- [Portainer](https://portainer.io/) - for managing all of your Docker containers
- [Watchtower](https://github.com/containerrr/watchtower) - for automatically updating running containers
- [NetData](https://my-netdata.io/) - for system resource monitoring
- [Bitwarden](https://bitwarden.com/) - open source password management solution

## Prereqs
* First pull down the repo and update cp the .env.example to a .env

## Instructions
* the following command will bring up your environment
                docker-compose up -d 


## Tips and Tricks
* gain shell access to a docker container
                docker-composer exec bash CONTAINER_NAME


# Known issues




# Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.